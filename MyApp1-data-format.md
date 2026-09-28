# MyApp1 — How to format questions for the database

This is how to write question and mark-scheme data so it builds into the calculator app and displays properly.

Everything lives in the WSL project `~/markscheme` (in Explorer: `\\wsl$\Ubuntu\home\asus_gaming\markscheme`).

---

## 1. The workflow

1. **Back up first:** `cp -a ~/markscheme ~/markscheme.bak-<something>`
2. Write or edit a text file in **`data/`**, e.g. `data/p1-mock-set-6.txt`. Use one file per paper.
3. **Check it:**
   ```bash
   cd ~/markscheme
   python3 tools/gen_db.py --check
   ```
   It should end with `N entries, 0 problems`. Fix anything it warns about.
4. **Generate the database:** `python3 tools/gen_db.py`. This rewrites `src/database.c`. Never edit that file by hand.
5. **Build:** `fxsdk build-cg`, then copy `MyApp1.g3a` to the calculator (see `README-fx-CG50.md`).

> Files are read in **alphabetical filename order**, and questions in file order. That's the order in which results appear in the app, so name files consistently: `p1-…`, `p2-…`, `p1-ial-june-2025.txt` and so on.

---

## 2. File layout

Every question is one block. The directives start with `@` at the very beginning of a line:

```
@paper P1 Mock Set 6

@q 1
@topic Trapezium rule, integration estimate
@marks 5
@question
...question text (LaTeX)...
@scheme
...mark scheme text (LaTeX)...

@q 2
@topic ...
```

| Directive | Rules |
|---|---|
| `@paper <name>` | Set it **once** at the top. It applies to every `@q` after it. Pattern: `P1 Mock Set 6`, `P2 SAMs`, `P1 Specimen`, `P1 June 2026`, `P1 IAL June 2025`. The results list turns it into a short tag: "Mock Set N" becomes `P1S6`; other names get initials, e.g. `P1 IAL June 2025` becomes `P1IJ25`. |
| `@q <number>` | Starts a new question. Printed as-is (`1`, `9b`…). **Must be unique within a paper.** |
| `@topic <text>` | Required, **42 characters max**. It isn't shown or searched in the app any more, but `--check` still requires it. |
| `@marks <n>` | Total marks for the question (a whole number). |
| `@question` | Everything after it, up to `@scheme`, is the question. Must not be empty. |
| `@scheme` | Everything after it, up to the next `@q`, is the mark scheme. Must not be empty. |

Any other `@word` is an error.

---

## 3. Text rules (both question and scheme)

- **ASCII only.** The calculator font has no other characters, so a curly quote, `°`, `π` or `–` becomes `?`. Write `pi` as `$\pi$`, degrees as the word `degrees`, and use straight quotes `"` and a plain hyphen `-`.
- **Line breaks come only from `\\`.** Pressing Enter in the file does *nothing*: lines are joined with spaces and blank lines are ignored. Put ` \\` at the end of every line that should start a new line on screen.
- **Maths goes in `$...$`.** There must be an even number of `$` (the check enforces this). Spaces inside `$...$` keep a formula together on one line on the detail screen.
- **Length limit:** each question or scheme must render to under about 4,095 characters. The check warns if it's too long; split very long schemes or cut repeated notes.
- A single word with no spaces that's longer than about 80 characters gets clipped in search. Put spaces inside long formulas.

---

## 4. LaTeX you can use

Only these commands are understood. Anything else is **silently dropped** on the calculator, and `--check` flags it.

| Kind | Commands |
|---|---|
| Structure | `\frac{a}{b}`, `\sqrt{x}`, `\sqrt[3]{x}`, `x^{2}`, `x_{n}`, `\int_{a}^{b}`, `\sum_{r=1}^{n}`, `\lim_{h \to 0}`, `\left( ... \right)` |
| Greek | `\pi \theta \alpha \beta \gamma \delta \epsilon \lambda \mu \sigma \phi \omega \Delta` |
| Relations / operators | `\leq \geq \neq \le \ge \ne \approx \equiv \in \times \div \cdot \pm \mp` |
| Arrows | `\to \rightarrow \Rightarrow \implies` |
| Functions | `\sin \cos \tan \sec \cosec \csc \cot \arctan \ln \log \exp` |
| Other | `\infty \ldots \cdots \therefore`, `\{ \}` (literal braces), `\text{...} \mathrm{...} \mathbf{...} \mathit{...} \mathbb{...}` |
| Spacing | `\quad \qquad \, \; \: \!` |

**Things that go wrong, and how to write them instead:**

| Don't write | Write | Why |
|---|---|---|
| `\frac12` | `\frac{1}{2}` | Always brace both halves. |
| `x^10`, `S_\infty`, `\int_\alpha^\beta` | `x^{10}`, `S_{\infty}`, `\int_{\alpha}^{\beta}` | `^` and `_` only take ONE character without braces. |
| `\sin\theta`, `n\pi`, `k\cosec x` | `\sin \theta`, `n \pi`, `k \cosec x` | Add a space between neighbouring commands. The search and results list glue them together otherwise (`sintheta`). |
| `\dfrac`, `\arccos`, `\binom`, `\overrightarrow`, `\circ`, `\cup`, `\cap`, `\leqslant`, `\operatorname`, `\hat`, `\dot`, `\angle`, `\mapsto`, `\propto`, `\Big` | `\frac`, `\cos^{-1}`, `^{n}C_{r}`, `\text{AB}`, `degrees`, `\text{ or }`, `\text{ and }`, `\leq`, `\text{name}`, … | Unknown commands vanish. |
| `\begin{array}...` or tables | Write rows as separate `\\` lines | Environments just become line breaks. |
| `\left(` with no `\right)` | Always pair them (`\right.` for "no bracket") | Otherwise the bracket swallows the rest of the line. |

**Vectors:** write column vectors as `(a, b, c)` and add the aside "(Vectors are given as column vectors.)". For i/j notation use `\mathbf{i}`.

---

## 5. Question conventions

```
@question
The curve $C$ has equation $y = \frac{1}{8}x^3 - \frac{24}{\sqrt{x}} + 1$ \\
(a) Find $\frac{dy}{dx}$, giving the answer in its simplest form. (3) \\
The point $P(4, -3)$ lies on $C$. \\
(b) Find the equation of the tangent to $C$ at $P$. (3)
```

- **Part labels** `(a)`, `(b)`, `(i)`, `(b)(ii)` go at the **start of a line** (right after `\\`), followed by a space. They are coloured, indented and spaced out on screen.
- **Part marks** `(3)` go as the **last thing on the line**, with a space before them. They show as a chip on the right.
- **Bullet points:** start the line with `- ` (hyphen, space). It shows as a bullet •.
- **Diagrams:** describe a figure in a line starting `(Diagram: ...)`. It's shown in grey. **Never make it the first line of `@question`**: the results list shows the first ~90 characters of the question, and they should be real question text. Real sentences like "Figure 1 shows ..." are fine first.
- **Don't include exam boilerplate.** Delete these on import: "In this question you must show all stages of your working. Solutions relying on calculator technology are not acceptable." and "(Solutions based entirely on graphical or numerical methods are not acceptable.)". Keep the part's `(N)` marks. Softer lines like "Show your working" are fine.

---

## 6. Mark scheme conventions

```
@scheme
(a) Area(R) $\approx \frac{1}{2} \times 0.5 \times \{ 1 + 2(e^{0.05} + e^{0.2}) + e^{0.8} \}$ \\
$= \frac{1}{4} \times 10.9075... = 2.73$ (2 dp) \\
B1 1.1b, M1 1.1b, A1 1.1b (3) \\
(b)(i) $\int_{0}^{2} (4 + e^{\frac{1}{5}x^2}) dx = 4(2) + 2.73 = 10.73$ B1ft 2.2a \\
Alt: $...alternative method line...$ M1 1.1b \\
Notes: \\
(a) B1: Outside brackets $\frac{1}{2} \times 0.5$ or 0.25 \\
M1: For structure of trapezium rule. \\
A1: Correct answer only of 2.73
```

- **One working step per line**, each ending `\\`.
- **Mark codes go at the END of the line**, separated by spaces: `M1 1.1b`, then `, A1 1.1b` if there's more than one. They are coloured (M blue, A green, B orange) and pushed to the right-hand edge. Recognised: `M1 A1 B1 E1 dM1 ddM1 A1* A1ft B1ft A0 B0 M0 …`
- **AO codes** (`1.1b`, `2.2a`, `3.1a`) go straight after their mark. They're shown small and grey. IAL papers have no AO codes: just write `M1, A1`.
- **Part total** `(3)` is the very last word of the part's final line.
- **Part labels** `(a)`, `(b)(i)` start the line, as in questions. On screen each part is separated by a rule.
- **Alternative methods:** a line starting `Alt:`, then the method's own lines.
- **Notes:** `Notes:` **alone on its own line** (it gets a heading band). Then one line per mark: `(a) M1: ...`, `A1: ...`, `dM1: ...`. `Note: ...` sentences are fine too.
- Quote a candidate's value like `"2.73"` with straight double quotes.

---

## 7. Search & results list — what users will see

- **Search matches only the question text**, as it appears on screen (not topic, paper, number or scheme). Users type what they see: `\frac{1}{2}` is found by typing `1/2`, and `\frac{dy}{dx}` by `(dy)/(dx)`.
- **Each result row is the literal start of the question** (about 90 characters over two lines). So the first line of `@question` matters: make it real, readable question text.

---

## 8. Checklist before building

- [ ] Backed up `~/markscheme`
- [ ] ASCII only, and no leftover exam boilerplate
- [ ] Every line ends in ` \\`
- [ ] Every `$` paired, and `^`/`_` braced when longer than one character
- [ ] Only commands from section 4
- [ ] Part labels at line starts, `(N)` marks at line ends, mark codes at the end of scheme lines
- [ ] `python3 tools/gen_db.py --check` gives **0 problems**
- [ ] `python3 tools/gen_db.py` then `fxsdk build-cg`

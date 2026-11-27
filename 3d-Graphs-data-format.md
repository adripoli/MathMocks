# 3d-Graphs — How to format questions, mark schemes and model answers

This is how to write the content that builds into the calculator app: **question papers, mark schemes and model answers**. It covers the file format, what the screen does with your text, and the standards every piece of content must meet.

Everything lives in the WSL project `~/markscheme` (in Explorer: `\\wsl$\Ubuntu\home\asus_gaming\markscheme`).

**The app has three tabs per question:** `F1` Question, `F2` Scheme, `F3` Model answer. Opening a result from the list lands on **Scheme**. If a question has no `@model`, the Model tab is greyed out and shows "No model answer for this question yet."

### The non-negotiables

1. **Questions are verbatim exam wording.** The first line is real question text, never a diagram note and never a "show all stages / calculator technology" notice. The `(N)` marks at line ends add up to `@marks`.
2. **Mark schemes are the official scheme, step by step**, mark codes at the end of each line, `Notes:` on its own line.
3. **Model answers show ALL the working**, the way a student would write it: one manipulation per line, every expansion, cancellation and arithmetic step, with a few words saying what each step does.
4. **Every number is verified, not guessed.** Recompute each figure with a script; never copy a number from an old answer or scheme without checking it.
5. **Nothing is built until the checks pass** (section 10), and an error found in existing content is fixed everywhere it lives (section 11).

### Contents

1. The workflow
2. File layout and where things live
3. Text rules (all three kinds of content)
4. LaTeX you can use
5. How the detail screen reads your text
6. Question papers: format and standards
7. Mark schemes: format and standards
8. Model answers: format and standards
9. Search and the results list
10. Checking everything (the quality gates)
11. Fixing an error you've found
12. Checklists
13. Gotchas

---

## 1. The workflow

**Adding or editing a question paper or mark scheme**

1. **Back up first:** `cp -a ~/markscheme ~/markscheme.bak-<something>`
2. Write or edit a text file in **`data/`**, e.g. `data/p1-mock-set-6.txt`. One file per paper.
3. Check it (section 10): `python3 tools/gen_db.py --check` and `python3 tools/check_standards.py`.
4. Generate the database: `python3 tools/gen_db.py`. This rewrites `src/database.c`. Never edit that file by hand.
5. Build: `fxsdk build-cg`, then copy `3d-Graphs.g3a` to the calculator (see `README-fx-CG50.md`).

**Adding or editing model answers**

1. Back up the project (step 1 above).
2. Write the answers in a **model-answer file** (`… MA.md`, section 8.1), one per paper. This file is the source of truth for the model answers.
3. Gate the file: `python3 tools/check_ma.py "<path to the MA file>"`. It must report `PROBLEMS 0`.
4. Put the answers into the data:
   - existing `@model` blocks are **replaced** by `python3 tools/sync_models.py --write "<MA file>"`
   - for a paper with no models yet, use `python3 tools/add_model_one.py "<MA file>" data/<paper>.txt --write`
5. Run the other checks, regenerate the database and build, as in steps 3 to 5 above.

> Don't hand-edit `@model` blocks inside `data/*.txt`. Edit the MA file and sync, so the two never drift apart.

> Files in `data/` are read in **alphabetical filename order**, and questions in file order. That is the order results appear in the app, so name files consistently: `p1-…`, `p2-…`, `p1-ial-june-2025.txt` and so on.

---

## 2. File layout and where things live

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
@model
...model answer (LaTeX), optional...

@q 2
@topic ...
```

| Directive | Rules |
|---|---|
| `@paper <name>` | Set it **once** at the top. It applies to every `@q` after it. Pattern: `P1 Mock Set 6`, `P2 SAMs`, `P1 Specimen`, `P1 June 2026`, `P1 IAL June 2025`. The results list turns it into a short tag: "Mock Set N" becomes `P1S6`; other names get initials, e.g. `P1 IAL June 2025` becomes `P1IJ25`. |
| `@level <A-Level or AS-Level>` | **Required**, set once at the top under `@paper`. Says which qualification the paper is. Edexcel UK AS papers (8MA0) and the IAL papers are `AS-Level`; everything else is `A-Level`. UK AS papers are named `AS1 June 2018`, `AS1 Mock Set 2`, `AS1 Sample` and so on. |
| `@q <number>` | Starts a new question. Printed as-is (`1`, `9b`…). **Must be unique within a paper.** |
| `@topic <text>` | Required, **42 characters max**. It isn't shown or searched in the app any more, but `--check` still requires it. |
| `@marks <n>` | Total marks for the question (a whole number). Must equal the sum of the question's `(N)` part marks. |
| `@question` | Everything after it, up to `@scheme`, is the question. Must not be empty. |
| `@scheme` | Everything after it, up to `@model` or the next `@q`, is the mark scheme. Must not be empty. |
| `@model` | **Optional.** Everything after it, up to the next `@q`, is the model answer. Leave it out and the Model tab is greyed out. |

Any other `@word` is an error.

**Where things live**

| What | Where |
|---|---|
| Content the app is built from | `~/markscheme/data/*.txt` |
| Generated database (never edit) | `~/markscheme/src/database.c` |
| Checking and sync tools | `~/markscheme/tools/` (`gen_db.py`, `check_standards.py`, `check_ma.py`, `sync_models.py`, `add_model_one.py`) |
| Model-answer source files | `Desktop\MathMocks\A-Level\A-Level Pure\<Set>\<Name> MA.md` (WSL: `/mnt/c/Users/Asus Gaming/Desktop/MathMocks/A-Level/A-Level Pure/<Set>/…`) |
| Original question and scheme sources | the `… QP.md` and `… MS.md` files in the same folders |
| Backups | `~/markscheme.bak-*` |



---

## 3. Text rules (question, scheme and model answer)

- **ASCII only.** The calculator font has no other characters, so a curly quote, `°`, `π` or `–` becomes `?`. Write `pi` as `$\pi$`, degrees as the word `degrees`, and use straight quotes `"` and a plain hyphen `-`.
- **Line breaks come only from `\\`.** Pressing Enter in the file does *nothing*: lines are joined with spaces and blank lines are ignored. Put ` \\` at the end of every line that should start a new line on screen. (A line that deliberately runs on into the next sentence may omit it, but that is rare. In model answers every line but the last must end in ` \\`.)
- **The last line of a block does not end in `\\`.**
- **Maths goes in `$...$`.** There must be an even number of `$` (the checks enforce this).
- **Question and scheme length limit:** each must render to under about 4,095 characters. `--check` flags it; split very long schemes or cut repeated notes. Model answers have no such limit but have their own renderer limits (section 8.6).
- A single word with no spaces that is longer than about 80 characters gets clipped in search. Put spaces inside long formulas.

---

## 4. LaTeX you can use

Only these commands are understood. Anything else is **silently dropped** on the calculator, and the checks flag it.

| Kind | Commands |
|---|---|
| Structure | `\frac{a}{b}`, `\sqrt{x}`, `\sqrt[3]{x}`, `x^{2}`, `x_{n}`, `\int_{a}^{b}`, `\sum_{r=1}^{n}`, `\lim_{h \to 0}`, `\left( ... \right)` |
| Greek | `\pi \theta \alpha \beta \gamma \delta \epsilon \lambda \mu \sigma \phi \omega \Delta` |
| Relations / operators | `\leq \geq \neq \le \ge \ne \approx \equiv \in \times \div \cdot \pm \mp` |
| Arrows | `\to \rightarrow \Rightarrow \implies` |
| Functions | `\sin \cos \tan \sec \cosec \csc \cot \arctan \ln \log \exp` |
| Other | `\infty \ldots \cdots \therefore`, `\{ \}` (literal braces), `\text{...} \mathrm{...} \mathbf{...} \mathit{...} \mathbb{...}` |
| Spacing | `\quad \qquad \, \; \: \!` |

Model answers are drawn by a slightly more capable renderer that also accepts `\dfrac \tfrac \varepsilon \varphi \leqslant \geqslant \dots \textbf \textit \mathcal \operatorname` and the escapes `\% \$ \# \_ \|`. **Don't rely on those**: stick to the table above everywhere so the content looks the same in every tab and in search.

**Things that go wrong, and how to write them instead:**

| Don't write | Write | Why |
|---|---|---|
| `\frac12` | `\frac{1}{2}` | Always brace both halves. |
| `x^10`, `S_\infty`, `\int_\alpha^\beta` | `x^{10}`, `S_{\infty}`, `\int_{\alpha}^{\beta}` | `^` and `_` only take ONE character without braces. |
| `\sin\theta`, `n\pi`, `k\cosec x` | `\sin \theta`, `n \pi`, `k \cosec x` | Add a space between neighbouring commands. The search and results list glue them together otherwise (`sintheta`). |
| `\angle ABC` | `angle $ABC$` (words), or name the angle with `\phi` | `\angle` is unknown and vanishes. |
| `\binom{6}{2}` | `6C2` | Unknown. |
| `\circ` (degrees) | the word `degrees` | Unknown. |
| `\dfrac`, `\arccos`, `\overrightarrow`, `\cup`, `\cap`, `\operatorname`, `\hat`, `\dot`, `\mapsto`, `\propto`, `\Big` | `\frac`, `\cos^{-1}`, `\text{AB}`, `\text{ or }`, `\text{ and }`, `\text{name}`, … | Unknown commands vanish. |
| `\because` | the word `since` | Unknown. (`\therefore` is fine; it draws as "so".) |
| `\begin{array}...` or tables | Write rows as separate `\\` lines | Environments just become line breaks. |
| `\left(` with no `\right)` | Always pair them (`\right.` for "no bracket") | Otherwise the bracket swallows the rest of the line. |

**Vectors:** write column vectors as `(a, b, c)` and add the aside "(Vectors are given as column vectors.)". Name vectors with `\text{AB}`, `\text{OA}`. For i/j/k notation use `\mathbf{i}`.

**Degrees and radians:** degrees are the word "degrees" (`$x = 70.9$ degrees`); radians are plain numbers or multiples of `\pi`.

---

## 5. How the detail screen reads your text

The screen is about 380 px wide, roughly 45 characters of plain text per line. Fractions are stacked, powers raised, roots drawn, Greek letters real glyphs. Each `\\`-separated line is a **paragraph**, and its **first word** decides how it is drawn.

| A line that starts with… | What the screen does | Tabs |
|---|---|---|
| `(a)`, `(b)(i)`, `(iii)` (1–4 lowercase letters in each bracket, optional colon) | **Part label**: navy, hanging indent, a rule drawn above | all |
| `- ` (hyphen, space) | Bullet | all |
| `(Diagram` | Grey text (a figure description) | all |
| `Notes:` **alone on the line** | A heading band | scheme |
| `Note:` (or `Notes:`) followed by text on the same line | Coloured lead word, hanging indent | scheme |
| `M1:`, `A1:`, `dM1:` … then text (the per-mark notes) | Coloured lead word, hanging indent | scheme |
| `Alt` … | Coloured, with a rule above (like a part label) | scheme |

| A word that is… | What the screen does | Tabs |
|---|---|---|
| a mark code: `M1 A1 B1 E1`, optional `d` / `dd` prefix, optional `ft`, optional `*`, optional trailing `, : ;` (`dM1`, `A1*`, `B1ft`, `M1,`) | Coloured (M blue, A green, B orange) | scheme only |
| an AO code straight after a mark: `1.1b`, `2.4`, `3.1a` | Small and grey | scheme only |
| the **last word of the line** and of the form `(3)` or `(10)` | A **marks chip**, pushed to the right edge | **every tab** |
| the trailing run of mark codes, their AO codes and the total | Pushed to the right edge as a block | scheme |

The marks chip is the important one: it is drawn in **every** tab, including model answers. A line that ends in a bare `(1)` or `(2)` therefore looks like marks. In a model answer never end a line that way (section 8.4).

A formula inside `$...$` stays on one line, and only breaks if it is wider than the screen. Text outside `$` wraps normally. So **keep each formula short** and spread a long chain over several lines.

Scrolling: UP/DOWN step, LEFT/RIGHT page, `F1`/`F2`/`F3` jump to a tab, EXIT goes back.

---

## 6. Question papers: format and standards

```
@question
The curve $C$ has equation $y = \frac{1}{8}x^3 - \frac{24}{\sqrt{x}} + 1$ \\
(a) Find $\frac{dy}{dx}$, giving the answer in its simplest form. (3) \\
The point $P(4, -3)$ lies on $C$. \\
(b) Find the equation of the tangent to $C$ at $P$. (3)
```

**Format**

- **Part labels** `(a)`, `(b)`, `(i)`, `(b)(ii)` go at the **start of a line** (right after `\\`), followed by a space.
- **Part marks** `(3)` go as the **last thing on the line**, with a space before them. They show as a chip on the right.
- **Bullet points:** start the line with `- `.
- **Tables of values:** one line, e.g. `Table of values: $x$ = 0, 0.5, 1 and $y$ = 1, 1.28, 1.65`.
- **Diagrams go AFTER the question text, never first.** Describe a figure in a line starting `(Diagram: ...)`. Real sentences like "Figure 1 shows ..." are fine to open with, since that is the exam's own wording. Where the figure carries information the question needs (a point read off a graph, a line through two labelled points), put those facts in the `(Diagram: ...)` line.

**Standards**

1. **Verbatim.** Reproduce the exam's wording and numbers exactly. Don't paraphrase, summarise or "improve" a question.
2. **The first line is genuine question text.** The results list shows the literal first ~90 characters of `@question`, and search looks only at the question text. A diagram description or a notice at the start would show up there instead of the question.
3. **Never include the "calculator technology" / "show all stages" heading.** Papers sometimes print "In this question you must show all stages of your working. Solutions relying on calculator technology are not acceptable." or "(Solutions based entirely on graphical or numerical methods are not acceptable.)". **Delete these entirely, don't move them.** They must not appear anywhere in `@question`. Keep a part's `(N)` marks when removing a bracketed aside. Softer lines such as "Show your working" or "You must show clearly how you obtained your answer" are fine to keep.
4. **The part marks add up.** The `(N)` chips at line ends sum to `@marks` exactly. (True of all 279 questions today; `check_standards.py` enforces it.)
5. **ASCII only, `$` paired, only the commands in section 4.**
6. `@topic` is a short label of 42 characters or fewer, written for you (it isn't shown in the app).

---

## 7. Mark schemes: format and standards

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

**Format**

- **One working step per line**, each ending `\\`.
- **Mark codes go at the END of the line**, separated by spaces: `M1 1.1b`, then `, A1 1.1b` if there is more than one. They are coloured and pushed to the right-hand edge. Recognised: `M1 A1 B1 E1 dM1 ddM1 A1* A1ft B1ft A0 B0 M0 …`
- **AO codes** (`1.1b`, `2.2a`, `3.1a`) go straight after their mark. IAL papers have no AO codes: just write `M1, A1`.
- **Part total** `(3)` is the very last word of the part's final line.
- **Part labels** `(a)`, `(b)(i)` start the line, as in questions. On screen each part is separated by a rule.
- **Alternative methods:** a line starting `Alt:`, then the method's own lines.
- **Notes:** `Notes:` **alone on its own line** (it gets a heading band). Then one line per mark: `(a) M1: ...`, `A1: ...`, `dM1: ...`. `Note: ...` sentences are fine too.
- Quote a candidate's value like `"2.73"` with straight double quotes.

**Standards**

1. **Faithful to the official scheme.** Mark codes, AO codes, the wording of the notes and the final answers are the examiners'. Don't restyle them.
2. **Don't "fix" a scheme for style.** Change scheme text only to correct a demonstrable error, and then by the procedure in section 11.
3. **Totals.** Each part's total `(N)` is the last word of that part's final line, and the part totals add up to `@marks`. The known exceptions: **P1 June 2026** has no marks at all (its source is prose worked solutions), a few single-part schemes print no total, and a scheme that includes an `Alt:` method repeats the total after it.
4. **Notes** appear when the official scheme has them. A scheme with no notes needs no `Notes:` line.
5. **The calculator-technology notice** is deleted from questions. Keep it out of schemes you write as well. (One IAL scheme, P1 IAL June 2024 Q6(a), still contains such a sentence; `check_standards.py` lists it as a note.)

---

## 8. Model answers: format and standards

A model answer is **the exact written working a student would produce to earn full marks**, not a summary and not just a final answer. Put yourself into the shoes of an a student doing the exam who would get full marks. The model answers are not there to explain the question, simply to show the workings of an A* student. Do not skip massive steps in algebra and show all working, but it does not have to be explained. 

### 8.1 The model-answer file

One file per paper, in the paper's MathMocks folder, named `<Set> - Pure <1|2> MA.md`. The answer lines go directly under `@question`:

```
@paper P1 Mock Set 6

@q 1
@topic Quadratic with no real roots
@marks 4
@question
Start with $3x^{2} + k = 5x + 2$ \\
Bring every term to one side (subtract $5x$ and $2$ from both sides): \\
$3x^{2} - 5x + k - 2 = 0$ \\
...
So $k > \frac{49}{12}$

@q 2
...
```

- `@paper`, `@q` and `@marks` must **match the data file exactly**. The sync tool refuses a mismatch in marks, and the check fails for any question in the paper that has no answer.
- `@topic` is a free label and is ignored.
- Every line except the last ends in ` \\`. The last line does not.
- Don't use `@scheme` or `@model` inside an MA file.

### 8.2 The level of detail

1. **One manipulation per line.** Never merge two steps. Each of these gets its own line: expanding a bracket, collecting like terms, moving a term across `=`, dividing or multiplying both sides, cancelling a common factor, factorising, rationalising a denominator, writing over a common denominator, using an identity, taking logs or exponentials, substituting a value (then evaluating it on the next line), simplifying a fraction, surd or index, and applying integration limits (upper limit line, lower limit line, then the subtraction).
2. **Say what you are doing**, in plain words, in front of or above the step: "Expand the bracket:", "Divide both sides by $(12 - 3y)$:", "Take natural logs of both sides:".
3. **Name every identity, rule and formula** the first time it is used: "Use $\sin 2\theta = 2\sin \theta \cos \theta$", "Product rule with $u = x$ and $v = e^{-2x}$", "Cosine rule in triangle $BOC$".
4. **Follow the method of the mark scheme**, so each mark is visibly earned. A valid alternative the scheme lists may be added as a short `Alt:` line.
5. **Define notation before using it** ("Let $t = \tan \theta$", "Let $u = 3x^{2} + 4$"), and substitute back at the end.
6. **Make validity decisions explicit.** Give the limits after a substitution. Reject a root with the reason ("$\log(-3)$ cannot be found", "$h$ cannot be negative"). State the condition before cancelling a factor ("not zero as $x \ne n\pi$").
7. **"Show that" questions** are worked forward to the printed result and end "as required". Never start from the result.
8. **The final answer** is on its own line, in exactly the form asked: exact or decimal, the right number of dp or sf, units, set notation.
9. **Modelling questions:** translate to maths first, then interpret the result in words with units, and give the reasons or limitations the question asks for.
10. **Iterations and roots:** list each iterate (using the calculator's ANS key so rounding doesn't build up), then justify the stated accuracy with a sign-change check at the ends of the interval it rounds to.
11. **Add a one-line check where it is cheap** (substitute back, test an endpoint).
12. **Read from a figure only what the question or scheme tells you.** If a value depends on a graph you can't see, follow the existing scheme rather than inventing it.

**The standard, by example.** The same step, written too tersely and as required:

```
Too terse (not acceptable):
$= \frac{2\tan\theta + \tan\theta(1-\tan^{2}\theta)}{(1-\tan^{2}\theta) - 2\tan^{2}\theta}$ \\
$= \frac{3\tan\theta - \tan^{3}\theta}{1 - 3\tan^{2}\theta}$ as required

Required:
Multiply the top and the bottom by $(1 - t^{2})$ to clear the small fractions \\
Top: $\left( \frac{2t}{1 - t^{2}} + t \right)(1 - t^{2}) = 2t + t(1 - t^{2})$ \\
$= 2t + t - t^{3}$ \\
$= 3t - t^{3}$ \\
Bottom: $\left( 1 - \frac{2t^{2}}{1 - t^{2}} \right)(1 - t^{2}) = (1 - t^{2}) - 2t^{2}$ \\
$= 1 - t^{2} - 2t^{2}$ \\
$= 1 - 3t^{2}$ \\
$\tan 3\theta = \frac{3t - t^{3}}{1 - 3t^{2}}$ \\
Replace $t$ by $\tan \theta$: \\
$\tan 3\theta = \frac{3\tan \theta - \tan^{3} \theta}{1 - 3\tan^{2} \theta}$ as required
```

### 8.3 Part labels and structure

- Put `(a)`, `(b)(i)`, `(ii)` at the **start** of a line, followed by a space; they get the navy label and a rule above.
- For a single-part question, just start the working (no label).
- Start a continuing equality with `=` on a new line rather than letting one long formula run on.
- A parenthetical aside that is not a part label is fine ("(Vectors are given as column vectors.)", "(Check: ...)"), but **don't open an aside with a short all-lowercase word and a closing bracket**, such as `(or)` or `(and)`: the screen would draw it as a part label.

### 8.4 Typography rules that the checker enforces

- **Never end a line with a bare `(1)`, `(2)` … `(10)`.** It is drawn as a blue marks chip. Label equations in words at the *start* of the line instead: "Equation 1, from the coefficients of $\sin \theta$: …", "Divide equation 2 by equation 1: …". The same goes for "equation (1)" at the end of a line.
- **Only the commands in section 4.** No `\angle`, `\binom`, `\circ`, `\cup`. Use words, `\phi`, or `6C1` instead.
- **ASCII only; every `$` paired; braces balanced on every line.**
- **Keep lines short.** Aim for no more than about 45 characters of rendered text per line, and split a long formula across lines with a leading `=`.
- **One equation per line.** Put text outside `$...$` so it wraps; formulas themselves don't wrap.

### 8.5 Getting the numbers right

1. **Compute every figure; never estimate it.** Use a script (Python with `mpmath` or `sympy` is ideal) and keep the output. An answer is not done until each number in it has been checked this way.
2. **Re-derive each answer independently.** Don't trust the mark scheme or an older model answer: errors have been found in both (section 11).
3. **The displayed lines must chain.** Each line must follow from the one before *as written*. Quote intermediate values to 4–6 significant figures so a reader who retypes them gets the same result.
4. **Rounding.** Carry at least two more figures than the answer asks for. If using a rounded intermediate value would change the final answer (say 1.1853 instead of 1.185225…), tell the reader to use the unrounded value, or use an exact fraction such as `\frac{7}{11}` instead.
5. **Verify the final answer against the mark scheme's.** If they differ, find out which is right (section 11) before writing anything.

### 8.6 Renderer limits

Each model answer is laid out as one page by a renderer with fixed memory: **4096 boxes, 8192 characters and 640 lines** per answer. The longest model answers today use **1373 boxes (34%), 1925 characters (23%) and 63 lines (10%)**, so there is about three times the room. Keep any answer under roughly half of each limit. The host sweep (section 10) reports overflow and a full pool; both must be 0.

---

## 9. Search and the results list

- **Search matches only the question text**, as it appears on screen (not topic, paper, number, scheme or model answer). Users type what they see: `\frac{1}{2}` is found by typing `1/2`, and `\frac{dy}{dx}` by `(dy)/(dx)`.
- **Each result row is the literal start of the question** (about 90 characters over two lines). So the opening of `@question` matters a lot: it must be genuine, readable question text.
  - **Never open with a `(Diagram: ...)` description.** Put diagram descriptions after the real question text.
  - **Never include the "show all stages of your working" / "calculator technology is not acceptable" notice.**
  - Either of these would otherwise show up as the search snippet and the results-list preview instead of the real question.

---

## 10. Checking everything (the quality gates)

Run these from `~/markscheme` before every build. Each is quick.

| Check | Command | What it catches |
|---|---|---|
| Database and LaTeX | `python3 tools/gen_db.py --check` | Missing or over-long `@topic`, duplicate `@q`, empty question or scheme, odd `$`, over-length question or scheme, LaTeX commands the calculator doesn't know (questions and schemes against the section 4 list; model answers against the slightly longer renderer list). Must end `N entries, 0 problems`. |
| Content standards | `python3 tools/check_standards.py` | **Hard rules** (must all pass): non-empty question and scheme, ASCII only, even `$`, no calculator-technology notice in a question or model, no question opening with `(Diagram`, question `(N)` chips adding up to `@marks`, no model line ending in a bare `(N)`, model lines ending in ` \\` (except the last). **Soft notes** (just reported): schemes whose totals don't add up, schemes with no `Notes:`, entries with no model. |
| A model-answer file | `python3 tools/check_ma.py "<MA file>"` | Every line but the last ends in ` \\`, the last doesn't; ASCII; `$` and braces balanced; no line ending in a bare `(N)`; no unknown LaTeX command; `@marks` matches the data; every data question in that paper has an answer. Must report `PROBLEMS 0`. |
| Placing models in the data | `python3 tools/sync_models.py "<MA file>"` (add `--write` to apply) | Shows, per paper, how many `@model` blocks it will replace or add, and refuses on a marks mismatch or an unmatched question. Run without `--write` first. |

`check_standards.py` was tested by running it on a scratch copy with deliberately broken entries (`C:\fxtmp\model\mutate_standards.py`). It caught every one: a diagram first line, non-ASCII, odd `$`, a model line ending in a chip, a missing `\\`, a banned notice, chips not adding up. It passes on the real data (279 entries, all hard rules). Today's soft notes are 60 entries with no model (the IAL papers), 43 schemes whose part totals don't add up (the exceptions listed in section 7), 66 schemes with no `Notes:` line, one scheme containing the calculator-technology sentence and one question line with no ` \\`.

**Look at it on a screen.** The checks can't tell you whether a page reads well, so each batch of model answers should also be viewed. A host test harness lives in `C:\fxtmp\model\host\` (a scratch folder, so rebuild it if it has been cleaned up). It compiles the real `main.c` on the PC and can:

- `./sweep2`: lay out and draw every question, scheme and model page, and report overflow, a full memory pool, and letters that don't match the plain-text render. The baseline is **777 pages, 219 of them model answers, overflow 0, pool-full 0**, and 9 expected differences (all `\sqrt[n]`).
- `bash shots_entry.sh "<paper>" <question number> [F1|F2|F3]`: take screenshots of every page of one entry's tab and tile them into `out_p1s1\<paper>_q<N>.png`.

For model answers, view at least the longest and the most algebraic pages of each paper.

**Order for a batch of model answers:** compute and re-derive → write the MA file → `check_ma.py` → `sync_models.py --write` → `gen_db.py --check` and `gen_db.py` → `check_standards.py` → host sweep and screenshots → `fxsdk build-cg`.

---

## 11. Fixing an error you've found

Errors have turned up in old model answers *and* in the mark scheme text itself (for example a scheme that gave `7 ≤ k < 9` when `k = 9` also works, and one that gave x₂ = −1.0664 instead of −1.0881). Treat a suspected error with care in both directions: don't ignore it, and don't "correct" something that is actually right.

1. **Be certain first.** Recompute the quantity exactly (a script with `mpmath`, `sympy` or exact fractions; try every sensible rounding of any intermediate value). Re-read the **original question wording** in the `QP.md` source. Only continue if it is wrong beyond doubt.
2. **Back up** every file you are about to change.
3. **Fix it everywhere it lives:**
   - the `data/<paper>.txt` scheme (or question) text
   - the matching MathMocks `MS.md` / `QP.md` source, so a future re-import doesn't bring it back
   - the model answer (in the MA file, then sync). Remove any note that referred to the old, wrong text.
4. **Make the smallest possible edit** (one line), with an exact-match replacement that refuses to run unless the old text occurs exactly once in each file.
5. **Show the diff** of question and scheme text against the backup. It should contain only the lines you meant to change.
6. **Re-run the gates** (section 10), regenerate the database and rebuild.
7. **Tell the person who owns the content** what was wrong, what you changed, and anything else you noticed but didn't change.

---

## 12. Checklists

**Question paper**

- [ ] Backed up `~/markscheme`
- [ ] Wording is verbatim from the exam; ASCII only
- [ ] `@question` opens with real question text, with no `(Diagram: ...)` first line and no calculator-technology / "show all stages" notice anywhere
- [ ] Every line ends in ` \\` (except the last), every `$` is paired
- [ ] Part labels at line starts, `(N)` marks at line ends, and the `(N)` marks add up to `@marks`
- [ ] Only commands from section 4, with `^`/`_` braced and spaces between neighbouring commands

**Mark scheme**

- [ ] The official scheme, step by step, one per line
- [ ] Mark codes at the end of the line, AO codes straight after (none for IAL)
- [ ] Part totals `(N)` at the end of each part; `Notes:` alone on its own line

**Model answer**

- [ ] One manipulation per line; no skipped algebra or arithmetic
- [ ] Every step says what it does; every identity or rule is named
- [ ] Notation defined, limits given, roots rejected with a reason, final answer in the requested form
- [ ] Every number computed by script and re-derived independently of the scheme; displayed lines chain
- [ ] No line ends in a bare `(N)`; no `\angle` / `\binom` / `\circ`; lines short; formulas on one line each
- [ ] `@q` numbers and `@marks` match the data

**Before building**

- [ ] `python3 tools/gen_db.py --check` gives **0 problems**
- [ ] `python3 tools/check_standards.py` gives **HARD rules: ALL PASS**
- [ ] `python3 tools/check_ma.py` gives **PROBLEMS 0** for every MA file you touched
- [ ] Host sweep: overflow 0, pool-full 0, and a look at the screenshots of the pages you changed
- [ ] `python3 tools/gen_db.py` then `fxsdk build-cg`

---

## 13. Gotchas

- **WSL quoting from Windows.** Single-quoting a `bash -lc` payload gets shredded, and variables, `$?` and backslashes get mangled. Use a double-quoted payload with `\$` for anything WSL should expand, and put loops or exit-code checks in a script file. `-lc` (a login shell) is needed so `fxsdk` is on the PATH.
- **Backslashes get eaten** by heredocs and some shells (`\\` becomes `\`, `\t` becomes a tab), silently corrupting LaTeX. Create any file containing LaTeX with a proper editor, not an `echo` or heredoc.
- **A bare `/mnt/c/...` argument to `wsl`** can be rewritten by Git Bash. Wrap the whole command in `bash -lc "..."`.
- **View WSL files from Windows** at `\\wsl$\Ubuntu\home\asus_gaming\markscheme`.
- **The tools read `~/markscheme/data` directly**, so run them after you have saved your edits, and use `sync_models.py` without `--write` first to see what it will do.

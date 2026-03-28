# Grade 8 Linear Equations — Interactive Learning Platform

> A fully self-contained, browser-based teaching and learning platform for **Grade 8 Module 4: Linear Equations**, built on the New York State Common Core Mathematics Curriculum (Eureka Math / EngageNY).

---

## Overview

This platform was designed to solve the hardest problem in online math teaching: **the missing feedback loop**. In a physical classroom, a teacher can walk around and see in thirty seconds who is stuck, who has the wrong method, and who is ready for extension work. Online, that disappears.

This single HTML file gives students a rich, interactive learning experience — visual explorers, guided practice, instant explanatory feedback — while giving the teacher a live dashboard showing every student's progress, common misconceptions, and who needs support right now.

**No installation. No login. No server. Open the file in any browser.**

---

## Screenshots

| Student View | Teacher Dashboard |
|---|---|
| Topic A — Writing & Solving | Live class progress |
| Interactive slope explorer | Misconception tracker |
| Simultaneous equations grapher | Private messaging |

---

## What's Inside

The platform covers all four topics of Grade 8 Module 4, with three interactive learning modes per topic.

### Topic A · Writing & Solving Linear Equations
**Standards: 8.EE.C.7 · 9 Lessons**

| Mode | What students do |
|---|---|
| Concept Explorer | Translate word problems into symbolic equations; identify linear vs. non-linear expressions; visual balance-scale equation solver |
| Guided Practice | Step-by-step problems from one-step equations through distributive property and variables on both sides |
| Classification Challenge | Determine whether an equation has one solution, no solution, or infinitely many solutions (Lesson 7 core concept) |

Key conceptual ideas addressed:
- Words → symbols (Descartes and symbolic language, Lesson 1)
- Linear vs. non-linear expressions (Lesson 2)
- Properties of Equality as balance (Lessons 4–6)
- The three solution types: `x = a`, `a = a`, `a = b` (Lesson 7)

---

### Topic B · Linear Equations in Two Variables & Their Graphs
**Standards: 8.EE.B.5 · 5 Lessons**

| Mode | What students do |
|---|---|
| Concept Explorer | Build a table of solutions for y = 2x + 1; click rows to plot points; horizontal and vertical line explorer |
| Graph Builder | Adjust slope and y-intercept with sliders; see table, equation, and graph update simultaneously |
| Rate & Distance | Paul's walking problem (Lesson 10); write proportional equations; compare two walkers by slope |

Key conceptual ideas addressed:
- A linear equation in two variables has infinitely many solutions (Lesson 12)
- Solutions form a straight line on the coordinate plane (Lesson 13)
- Horizontal lines (y = c) and vertical lines (x = c) as special cases (Lesson 14)
- Unit rate as the slope of a proportional relationship (Lessons 10–11)

---

### Topic C · Slope & Equations of Lines
**Standards: 8.EE.B.5, 8.EE.B.6 · 9 Lessons**

| Mode | What students do |
|---|---|
| Slope Explorer | Drag rise and run sliders; watch annotated arrows update on a live graph; compute slope from two points |
| Equation Builder | Adjust m and b in y = mx + b; read off y-intercept, direction, and equation simultaneously |
| Similar Triangles & Slope | Visual proof that slope is constant along any line; two pairs of points, two similar triangles, same ratio |

Key conceptual ideas addressed:
- Slope as steepness — a number, not just a formula (Lesson 15)
- Slope formula: m = (y₂ − y₁) / (x₂ − x₁) (Lesson 16)
- Why any two points on the same line give the same slope: similar triangles proof (Lesson 16–17)
- Writing y = mx + b from a point and slope (Lesson 21)
- Constant rate of change as slope (Lesson 22)

---

### Topic D · Solving Simultaneous Linear Equations
**Standards: 8.EE.C.8 · 7 Lessons**

| Mode | What students do |
|---|---|
| Introduction | Derek's basketball scoring problem (Lesson 24); identify which (x, y) pair satisfies both equations simultaneously |
| Graphical Method | Drag two lines on a shared graph; watch the intersection (solution) update in real time; discover parallel and identical line cases |
| Substitution | Worked step-by-step examples; guided practice; challenge problem using y = 7x − 2 from Lesson 27 |

Key conceptual ideas addressed:
- A system of linear equations as two conditions that must hold simultaneously (Lesson 24)
- The solution as the intersection point of two graphs (Lessons 24–25)
- Three possible outcomes: one solution, no solution (parallel), infinitely many solutions (same line) (Lesson 27)
- Substitution method — algebraic solution without graphing (Lesson 27)

---

## Teacher Dashboard

The teacher view (accessible from the sidebar) provides:

- **Live student cards** — name, current topic, current question, progress bar, and score
- **Status indicators** — green (active), amber (needs help), grey (not started)
- **Private notes** — click any student card to send an inline hint they see immediately
- **Broadcast hint** — send a class-wide message when multiple students share a misconception
- **Spotlight** — share one student's work anonymously with the whole class for discussion
- **Misconception tracker** — automatically surfaces the most common wrong answers this session

---

## Pedagogical Design Principles

This platform was built around five principles drawn directly from the Eureka Math teacher materials:

1. **Sequence before formula** — Students encounter the concept before the vocabulary. The Δy column appears after students have already noticed the constant change. The word "slope" arrives after students have measured steepness.

2. **Three representations in sync** — Table, graph, and equation are always visible together so students build connections, not isolated facts.

3. **Explanatory feedback, not just right/wrong** — Every incorrect answer triggers a specific hint pointing to the exact misconception, not a generic "try again."

4. **Scaffolded unlocking** — Questions unlock sequentially. Students cannot skip the conceptual steps to reach the formula.

5. **Real-world context is load-bearing** — Scenarios (Paul's walk, Derek's basketball score, Layla's data plan) are chosen so that the y-intercept, slope, and solution have plain-English meaning — not just symbolic values.

---

## Getting Started

### For teachers

1. Download `grade8_linear_equations_platform.html`
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. Share the same file with students (via Google Classroom, email, or school LMS)
4. Open your own copy and navigate to **Teacher View** in the sidebar
5. Students open their copy and work through topics at their own pace

> **Note:** The teacher dashboard in this version is a demonstration interface. For live multi-student synchronisation, see [Planned Features](#planned-features) below.

### For students

1. Open the HTML file in your browser
2. Start at **Topic A** or wherever your class is in the module
3. Work through the three tabs in each topic: Concept Explorer → Guided Practice → Challenge
4. Use the ✋ button (bottom right) to raise your hand and signal your teacher

---

## File Structure

```
grade8_linear_equations_platform.html   ← The entire platform (single file)
README.md                               ← This file
```

The platform is intentionally a **single self-contained HTML file** with no external dependencies except Chart.js (loaded from a CDN). This means:

- It works offline once the page has loaded
- It can be emailed, shared via USB, or uploaded to any LMS
- No build step, no npm, no framework — just open and use

---

## Technical Details

| Detail | Value |
|---|---|
| File type | Single HTML file |
| External dependency | Chart.js 4.4.1 (cdnjs.cloudflare.com) |
| Browser support | Chrome 90+, Firefox 88+, Safari 14+, Edge 90+ |
| Screen size | Optimised for 1280px+ (laptop/desktop); usable on tablet |
| Storage | None — no data is stored or transmitted |
| Internet required | Only for Chart.js CDN on first load |

All interactivity is pure HTML, CSS, and vanilla JavaScript. No frameworks, no build tools, no server required.

---

## Curriculum Alignment

| Topic | Standard | Lessons | Core skills |
|---|---|---|---|
| A | 8.EE.C.7a | 1–9 | Write equations from language; classify solution types |
| A | 8.EE.C.7b | 4–8 | Solve with distributive property; combine like terms |
| B | 8.EE.B.5 | 10–14 | Proportional relationships; graph linear equations in two variables |
| C | 8.EE.B.5 | 15, 22–23 | Unit rate as slope; compare proportional relationships |
| C | 8.EE.B.6 | 16–21 | Slope formula; similar triangles proof; y = mx + b |
| D | 8.EE.C.8a | 24–25 | Understand systems; graphical solution |
| D | 8.EE.C.8b | 26–28 | Solve systems algebraically (substitution) |
| D | 8.EE.C.8c | 27–28 | Real-world problems using systems |

Source materials: *New York State Common Core Mathematics Curriculum, Grade 8 Module 4: Linear Equations* (Eureka Math / EngageNY, © 2015 Great Minds). Licensed under [Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported](https://creativecommons.org/licenses/by-nc-sa/3.0/).

---

## Planned Features

- [ ] **Local storage** — save student progress across sessions in the same browser
- [ ] **Firebase integration** — real-time teacher dashboard with live multi-student data
- [ ] **Student login** — class code system so teacher can identify individual students
- [ ] **Mid-module assessment** — timed quiz covering Topics A and B with auto-scoring
- [ ] **End-of-module assessment** — full summative assessment aligned to Eureka Math rubric
- [ ] **Printable worksheets** — generate PDF student worksheets from any topic with one click
- [ ] **Mobile layout** — responsive redesign for phones and small tablets
- [ ] **Arabic RTL support** — right-to-left layout for Arabic-medium classrooms
- [ ] **Teacher content editor** — paste in your own scenarios and questions without editing HTML
- [ ] **Additional modules** — Module 5 (Examples of Functions), Module 6 (Linear Functions), Module 7 (Introduction to Irrational Numbers)

---

## Contributing

Contributions are welcome. If you are a math teacher and spot a misconception in the feedback text, an error in an answer key, or a missed pedagogical opportunity — please open an issue or submit a pull request.

If you build a new topic, lesson, or interactive tool using this platform as a base, please share it so other teachers can benefit.

### Contribution guidelines

- Keep the platform as a single HTML file where possible
- All feedback text should be **explanatory**, not just "correct" or "wrong"
- New questions should unlock sequentially — students should not be able to skip conceptual steps
- Test in at least two browsers before submitting

---

## License

The platform code (HTML, CSS, JavaScript) is released under the **MIT License** — free to use, modify, and distribute for any purpose, including commercial use.

The mathematical content is adapted from Eureka Math Grade 8 Module 4, which is licensed under [CC BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/). Any derivative content must be attributed and must not be used for commercial purposes.

---

## Acknowledgements

- **Curriculum:** Great Minds / EngageNY — *Eureka Math Grade 8 Module 4: Linear Equations* (2015)
- **Similar triangles and slope approach:** Prof. Hung-Hsi Wu, 2013 MPDI notes (used with permission in the original curriculum)
- **Chart.js:** Open Charts / Chart.js contributors (MIT License)
- **Designed for:** Grade 8 mathematics students and their teachers

---

*Built to make online math feel like the real thing.*

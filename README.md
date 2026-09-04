# Month 1 Study Guide Flash Cards

A professional, printable flash-card set based on the **Month 1 Self-Study Guide: UI, Modern CSS & React Foundations**.

The set is designed for active recall and visual learning. It covers HTML foundations, modern CSS layout, JavaScript data transformations, asynchronous requests, React architecture, Next.js client boundaries, DevTools, and AI-assisted code review.

## Contents

- `Month_1_Self_Study_Guide_Typed.docx` - Original typed study guide.
- `Month_1_Study_Guide_Flash_Cards.md` - Markdown version of the 48 study questions and answers.
- `Month_1_Study_Guide_Printable_Cards.html` - Editable print layout with centered questions, centered answers, topic labels, code examples, and crop marks.
- `Month_1_Study_Guide_Printable_Cards.pdf` - Ready-to-print landscape PDF of the flash cards.
- `Month_1_Visual_Summary.html` - Editable one-page visual reference sheet.
- `Month_1_Visual_Summary.pdf` - Ready-to-print visual summary PDF.
- `Month_1_Visual_Study_Guide.html` - Editable five-page visual companion to the full study guide.
- `Month_1_Visual_Study_Guide.pdf` - Ready-to-print visual study guide PDF.
- `Month_1_Practice_Worksheet.html` - Editable active-recall worksheet with writing space.
- `Month_1_Practice_Worksheet.pdf` - Ready-to-print practice worksheet PDF.
- `Month_1_Interactive_Learning.html` - Dependency-free interactive learning program with visual lessons, labs, quizzes, progress tracking, and a capstone path.

## Flash-Card Format

Each landscape letter page contains two 5 x 3 inch card pairs:

- Question/front on the left.
- Matching answer/back on the right.
- Formal academic typography and restrained navy styling.
- Topic label in the footer.
- Compact code examples on syntax-heavy cards.
- Corner crop marks and solid borders for trimming.

## Printing Instructions

1. Open `Month_1_Study_Guide_Printable_Cards.pdf`.
2. Print in **landscape** orientation.
3. Select **Actual Size** or **100% scale**. Do not use Fit to Page.
4. Print one test page first.
5. Cut around the solid card borders and the center divider.
6. Glue each question and answer pair onto a landscape 3 x 5 index card, or fold the pair if using heavier paper.

For the visual references, print `Month_1_Visual_Summary.pdf` or `Month_1_Visual_Study_Guide.pdf` in landscape at 100% scale.

The visual study guide presents the complete month as a roadmap, then explains the box model, Flexbox, data transformations, React data flow, request debugging, AI code review, spaced review, and the month-end assessment using diagrams and structured panels.

The practice worksheet is designed to be completed before reviewing the flash-card answers. It includes 29 prompts, code-writing questions, diagram prompts, and a confidence tracker.

The interactive learning program is a self-paced course, not just a reference page. The home screen shows a course syllabus with six modules (HTML, CSS, JavaScript, React, Debugging, Capstone) that unlock in order: each module is locked (🔒 in the sidebar) until you pass the previous module's quiz (or, for the capstone gate, finish the debugging diagnosis), and a "Start the course" / "Continue: Module N" / "View your certificate" button always points at the right next step. Each unlocked module includes a real, well-reviewed YouTube tutorial from a reputable channel (freeCodeCamp.org, Chrome for Developers, Bro Code) covering the topic in depth, shown as a click-to-play video card, plus a sliding deck of 4-6 in-depth topic pages you page through with Prev/Next buttons, dot indicators, keyboard arrow keys, or a swipe gesture, and a 5-question graded quiz with a running score (the debugging module ends in a written diagnosis instead). Training-depth topics now covered include: semantic regions, forms/validation, tables, lists/links, and HTML5 input types; the box model, Flexbox, Grid, cascade/specificity, positioning, custom properties, and responsive units; JavaScript array methods, closures, async/await, destructuring, variable scope, function types, and error handling/JSON; React data flow, hooks, custom hooks, JSX rules, composition, and controlled forms; console/network/breakpoints/stack traces, common error types, network waterfalls, and React-specific pitfalls; and a capstone covering component hierarchy, a code-review checklist, and a final QA/deployment checklist. It saves quiz scores, checklist progress, and the teach-back response in the browser's local storage. Finish every module quiz and the capstone checklist to unlock a printable certificate of completion.

**To play the videos inline**, YouTube requires the page to be served over `http://` rather than opened directly from disk (`file://`). Start a local server from this folder and open the page through it:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000/Month_1_Interactive_Learning.html` in your browser. If you open the file directly instead, the video cards still show a thumbnail and a "Watch on YouTube" fallback link that opens the video in a new tab.

## Study Routine

- Cover the answer and explain the question aloud.
- Use the code example to connect the definition to a practical pattern.
- Mark cards for review after 1 day, 3 days, and 7 days.
- Practice contrast pairs such as props vs. state, mutation vs. immutable update, and `content-box` vs. `border-box`.
- Consider a card mastered only after defining and applying the concept correctly twice without notes.

## Source Topics

- Semantic HTML, forms, accessibility, links, lists, tables, images, and media.
- CSS box model, `border-box`, Flexbox, responsive constraints, and DevTools.
- JavaScript values and references, `map`, `filter`, spread syntax, Promises, and `fetch`.
- React props, state, functional updates, derived state, keys, reconciliation, and data flow.
- Next.js Server and Client Components, hydration, debugging, and AI-generated code review.

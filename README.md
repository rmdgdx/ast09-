# AST09 · Data Science and Analysis — Course Website

**Rizal Technological University · First Semester, A.Y. 2026–2027**
Course Professor: **Dr. Ryan Manuel D. Guido** · Teaching Assistant: **Instr. Princess B. Tucio**

This repository hosts the complete course syllabus and the twelve interactive chapter lectures for AST09 (Data Science and Analysis), a 3-unit, 15-week lecture course (prerequisite: AST06) covering inferential and advanced statistics, the principles of data science, the Python ecosystem via Google Colab, and a research capstone toward a Scopus-indexed conference paper.

## Contents

| Path | Description |
|---|---|
| `index.html` | The full course syllabus (overview, outcomes, outline, learning plan, course map, grading, capstone, readings, policies) with links to all lectures |
| `chapters/chapter-01.html` … `chapter-12.html` | Interactive chapter lectures — each with worked examples, a self-check quiz, a 20-item HOTS test, a 20-item HOTS reinforcement assignment, and a 3-item futures essay |
| `assets/banner.png` | Google Classroom banner (2000×500) |
| `assets/banner-overlay-safe.png` | Banner variant with the lower-left kept clear for Classroom's class-name overlay |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (no Jekyll processing) |

## How to publish with GitHub Pages

1. Create a new repository on GitHub (e.g., `ast09-syllabus`). Public repositories get free GitHub Pages hosting.
2. Upload **all files and folders** in this package to the repository root (drag-and-drop on github.com works: *Add file → Upload files*). Keep the folder structure intact.
3. In the repository, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose the **main** branch and the **/ (root)** folder, then **Save**.
5. After a minute or two, the site is live at:

   ```
   https://<your-username>.github.io/ast09-syllabus/
   ```

   Individual lectures resolve automatically, e.g.
   `https://<your-username>.github.io/ast09-syllabus/chapters/chapter-03.html`

6. Share the main URL with the class (it also works pasted into Google Classroom as a Material link). Any file you later edit and re-upload republishes automatically.

## Notes

- Everything is self-contained static HTML — no build step, no dependencies, no server code.
- Pages are responsive (phone-friendly) and print-friendly (the syllabus hides its navigation bar when printed).
- Assessment answer keys are inside `<details>` dropdowns in each chapter; students tap **Show answer** to self-check.

---
© Rizal Technological University · Prepared for AST09, A.Y. 2026–2027 · Dr. Ryan Manuel D. Guido

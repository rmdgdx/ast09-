# Data Science and Analysis (AST09) — Course Site

The AST09 course syllabus and interactive chapter lectures for GitHub Pages,
built so chapters can be posted **one at a time** during the semester.

## What's here

```
index.html          the course syllabus + Interactive Chapter Lectures section
chapter01.html      Chapter 1 (posted — linked from the Wk 1 row)
chapters/           upload later chapters here (or at the root); see chapters/README.md
.github/workflows/  optional GitHub Pages deployment via Actions
.nojekyll           serve files verbatim
```

## First-time setup

1. Create a GitHub repository and upload ALL of these files/folders to its root.
2. Settings → Pages → Build and deployment → Source: "Deploy from a branch"
   → branch `main`, folder `/ (root)` → Save.
3. Open `https://<username>.github.io/<repo>/` after a minute.

## Posting a chapter during the semester

Upload the chapter's HTML file to the repo (root or `chapters/` folder), named
`chapter-NN.html` or `chapterNN.html` — e.g. `chapter02.html` for Week 2.
On the next page load, that row in **Interactive Chapter Lectures** switches
from *coming soon* to *posted* with a working link. Nothing else to edit.

How it works: the page sends a HEAD request for each chapter's accepted
filenames and links the first one that exists. Chapter 1 is hard-linked, so it
is always shown as posted.

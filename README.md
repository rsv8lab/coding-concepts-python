# Coding Concepts — Learning Studio

A nine-module, self-contained interactive study book covering the Python data-science stack, built around one consistent pattern per chapter: a **W/H concept table** (What / Why / How / When / Where), a **mnemonic**, a **copyable code example**, and a **five-step learning cycle** ending in a checklist and reflection notes.

## Chapters

| # | Module | Topic |
|---|--------|-------|
| 1 | [chapter1.html](chapter1.html) | Python Data Types — The Foundation |
| 2 | [chapter2.html](chapter2.html) | NumPy — The Numeric Engine |
| 3 | [chapter3.html](chapter3.html) | Pandas — Tabular Data |
| 4 | [chapter4.html](chapter4.html) | Matplotlib & Seaborn — Seeing Data |
| 5 | [chapter5.html](chapter5.html) | SciPy — Scientific Operations |
| 6 | [chapter6.html](chapter6.html) | openpyxl — Reading & Writing Excel |
| 7 | [chapter7.html](chapter7.html) | GUI — PySide6 |
| 8 | [chapter8.html](chapter8.html) | scikit-learn — Machine Learning |
| 9 | [chapter9.html](chapter9.html) | Advanced AI — Beyond Classical ML |

Start at [index.html](index.html) — every chapter links to every other chapter via the nav bar at the top, plus a "back to book overview" link.

## Running it

No build step, no dependencies. It's plain HTML/CSS/JS.

- **Locally:** open `index.html` in any browser.
- **GitHub Pages:** push this repo, then enable Pages (Settings → Pages → Deploy from branch → `main` / root). The book will be live at `https://<your-username>.github.io/<repo-name>/`.

## How progress is saved

Each chapter's checklist and reflection notes are saved with `localStorage`, scoped per chapter (`coding-concepts-ch1` … `coding-concepts-ch9`). Nothing is sent to a server — progress lives only in the browser that opened it, and a "Reset chapter progress" button on each page clears that chapter's saved state.

## Author

Kamol Das · CSE, Oxford University

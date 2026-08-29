# Dmitriy's IELTS Notes

Personal IELTS preparation site — a single-page app covering Reading, Listening, Speaking, and Writing in depth.

**Live site → [your-domain-here]**

---

## What this is

A self-contained study reference built during preparation for the IELTS Academic test. It covers:

- **Reading** — question type strategies and practice links (Engnovate)
- **Listening** — section breakdown, tip cards, and common error patterns
- **Speaking** — test format, Part 1/2/3 structures, how I practised (ChatGPT Live Voice + question bank), scoring criteria table (Bands 5–9), full phrase & collocation bank (downloadable PDF), and 607 practice questions (downloadable xlsx)
- **Writing** — scoring criteria (official rubric images), evaluator prompts for Gemini Pro, grammar rules, collocations, and 13 type-specific pages (7 Task 1 + 6 Task 2), each with a first-person approach guide, structure table, language bank, common errors, model essay, and practice prompts

---

## Files

| File | Description |
|---|---|
| `index.html` | The entire site — one self-contained HTML file, no framework, no build step |
| `IELTS_Speaking_Vocabulary_Bank.pdf` | Full speaking phrase & collocation bank (linked from the Speaking page) |
| `IELTS_Speaking_Questions_Jan_Aug_2026.xlsx` | 607 speaking questions (Part 1/2/3) sourced from Jan–Aug 2026 test reports |
| `README.md` | This file |

The evaluator prompts for Task 1 and Task 2 are embedded directly inside `index.html`.

---

## How to run locally

No server needed. Just open `index.html` in a browser:

```bash
git clone https://github.com/YOUR_USERNAME/ielts-prep
cd ielts-prep
open index.html        # macOS
# or: xdg-open index.html   (Linux)
# or: double-click the file in Explorer (Windows)
```

The PDF and xlsx downloads will work correctly when opened from the same folder.

---

## Stack

- Plain HTML, CSS, and vanilla JavaScript — no framework, no dependencies
- Single-file SPA: pages are shown/hidden by a `showPage()` function
- All content is static — no backend, no database
- External image URLs: task images from [engnovate.com](https://engnovate.com), rubric image from Springer (open-access, CC BY 4.0)

---

## Sources and credits

- IELTS Writing Band Descriptors (public version, May 2023) — © British Council, IDP: IELTS Australia, Cambridge English
- Rubric image: Nguyen & Le (2022), *Language Testing in Asia*, [doi:10.1186/s40468-022-00206-0](https://doi.org/10.1186/s40468-022-00206-0), CC BY 4.0
- Task 1 practice images: [engnovate.com](https://engnovate.com)
- Model essays: IELTS Academic Writing Master Handbook
- Speaking questions: compiled from IELTS test reports (Jan–Aug 2026), r/IELTS, IELTS Mentor, Assistant IELTS app

---

## Licence

Personal study notes — not affiliated with or endorsed by IELTS, British Council, IDP, or Cambridge English.

# Pre-Calculus Study Plan

A small static page that organizes a 7-day pre-calculus review schedule (Wed May 13 → Tue May 19) into clickable per-day cards. Click any section title and a side-by-side viewer opens — exercises on the left, solutions on the right.

## Run it

Open `index.html` in a browser, or visit the GitHub Pages URL once hosted. That's it.

Your check-off state is saved in your browser's `localStorage` (key `precalc_shared_v1`). Nothing is sent anywhere — clearing site data resets the progress bar.

## What's in `precalc_exercises/`

66 PDFs covering 35 sections: an exercises sheet and (where available) a solutions sheet for each section. Shared with the instructor's permission.

Five sections (9.1, 9.3, 10.2, 10.3, and the second half of 10.1) only have an exercises PDF — the solutions pane displays "Solutions not posted" for those.

## Sections covered

- **Day 1** — Chapter 0.3, Sections 1.1–1.5
- **Day 2** — Chapter 2.6, Chapter 3 Extension, Sections 3.2 / 3.5 / 3.7 / 3.8
- **Day 3** — Sections 4.1 / 4.3 / 4.5 / 4.6 / 5.1 / 5.2
- **Day 4** — Sections 5.4 / 6.1 / 6.2 / 6.3 / 7.1
- **Day 5** — Sections 7.2 / 7.3 / 7.4 / 8.1 / 8.2 / 8.3
- **Day 6** — Sections 8.4 / 9.1 / 9.3 / 10.1 / 10.2 / 10.3
- **Day 7** — Broad review before the final on May 20

## Customizing the schedule

The `days` array in the script is the only data source. Each entry has `num`, `date`, `theme`, `color`, `bg`, and a `files[]` list. The `pdfMap` object right after it maps each study-plan title to the matching PDF filenames. Edit those to retarget the plan to a different week or course.

## License

The HTML, CSS, and JavaScript are released under the MIT License (see `LICENSE`). The PDFs in `precalc_exercises/` remain the property of their original author and are included here with permission — please don't redistribute them outside this project's context.

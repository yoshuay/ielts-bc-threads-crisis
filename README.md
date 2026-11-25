# IELTS British Council Indonesia — Meta Threads Crisis Intelligence

Interactive bilingual (`ID` / `EN`) crisis intelligence dashboard, severity-classified dataset, thematic analysis, root cause analysis (Pareto, Multi-Track 5 Whys, 6M Fishbone), and interactive operations/QA prioritization board based on Meta Threads posts and replies observed between **25 October 2026 – 25 November 2026**.

## Data Collection Methodology
- **Platform & Session**: Meta Threads (`threads.com`) accessed via an authenticated session.
- **Observation Window**: October 25 – November 25, 2026 (WIB / UTC+7), focused on Indonesian-language posts and replies from Indonesia regarding British Council IELTS testing.
- **Search Coverage**: Checked **Top** and **Recent** tabs alongside Advanced Search date filters (`exact_match=true` and `false`) across `#ielts`, `#britishcouncil`, `ielts british council` (scrolled through Oct 24, 2026), `British Council Indonesia`, `tes IELTS British Council`, `IELTS BC`, and supporting local queries (`British Council`, `tes di BC`, `ielts idp bc`).
- **Coding (`n = 55`)**: Original posts and substantive replies coded across 4 severity tiers (`Critical`, `High`, `Medium`, `Low`), 9 issue categories, 6 overarching themes (`T1`–`T6`), sentiment, and venue/branch mentions. Original posts remain verbatim in Indonesian with an on-demand English translation toggle in the UI.

## Repository Contents
- `index.html` — Self-contained bilingual (`ID`/`EN`) interactive web dashboard.
- `threads_ielts_bc_indonesia_raw.md` — Verbatim raw dataset from Meta Threads.
- `ielts_bc_threads_severity_worksheet.xlsx` — Multi-sheet Excel workbook with native charts, severity classification, RCA/5 Whys, and operational recommendations.
- `thematic_analysis_report.md` & `charts/` — Thematic breakdown and PNG visualizations.
- `crisis_management_analysis.md` — Full RCA and operational recommendations.

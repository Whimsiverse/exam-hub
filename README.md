# DDD Mini Paper Studio

Four original scenario-based practice papers for IT2140. Each has 25 questions, five options per question, and 100% multiple-selection questions.

| Paper | Lectures | Focus |
|---|---|---|
| 01 | 01, 02, 03 | DBMS decisions, SQL, constraints and joins |
| 02 | 04, 05 | Large EER scenarios and relational mapping |
| 03 | 06, 07 | Dependencies, normalisation and database programs |
| 04 | 08, 09 | Relational algebra and NoSQL decisions |

## Open or upload

Open `index.html` with all adjacent files and the assets folder intact. No installation, account, server or build is needed. The separate standalone HTML edition embeds its assets and can be opened by itself.

For GitHub: extract the ZIP and upload its **contents**, including `index.html`, `app.js`, `style.css`, `papers.js` and the `assets` directory, to your repository root. Uploading a ZIP alone does not create a working website. This package is ready for a static web host; repository upload alone does not publish it.

## Marking and attempts

Each correct selected option: +1. Each incorrect selected option: −1. Missed options: 0. Each question is clamped to a minimum of 1, including an unanswered question. Maximum per question equals its number of correct options. This is the requested practice rule, not an official examination policy. Exact-match counts and minimum-floor information are also reported.

All questions allow multiple selections. Selections and flags are saved separately for each paper in browser local storage. Submit on the end-of-paper review screen to freeze the attempt and reveal all option explanations. New attempt clears only that paper’s saved attempt. Browser data does not sync between devices or origins; file-opening storage behaviour depends on the browser. If storage is unavailable the current tab still works.

The answer lock is an ordinary study-interface lock, not secure proctoring: this static, offline application contains its answer keys in the source. It hides answers during normal use, but cannot prevent source inspection. No student data is sent to a server.

## Content and sources

Based on the supplied IT2140 lecture decks 01–09 and their supporting labs/tutorials. Questions and both EER diagrams are original. The diagrams explicitly state their scenario assumptions; do not import business rules from other examples. SQL questions use SQL Server/T-SQL unless stated otherwise. Relational algebra uses set semantics where specified. Each submitted question includes a course reference and a reason for every option.

To edit content, update `paper1.json` through `paper4.json` and rebuild `papers.js` as `window.PAPERS=[...the four paper objects...];`. The application reads `papers.js`, not the JSON files directly.

Nunito is bundled under the SIL Open Font License; see `assets/OFL-Nunito.txt`. Font source: https://github.com/googlefonts/nunito. Static font instances are derived from the supplied Nunito variable font. The hub uses no external scripts, analytics, or network fonts.

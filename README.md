# K-12 AI examples

Two examples from Brendan Bartanen's talk "Innovation with Guardrails" to the UVA K-12 Advisory Council (Virginia school superintendents), October 2, 2026. They illustrate what a person can build with current AI coding tools. Both were built by an AI coding tool (Claude Code) under his direction on September 30 and October 1, 2026.

Live site: https://brendanbartanen-svg.github.io/k12-ai-examples/

## Newton's Lab

A 3D student-facing lab on Newton's three laws of motion, rebuilt from the files Brendan taught from as an 8th-grade science teacher in 2013-15 and aligned to Virginia Science SOL PS.8.

- **First Law.** Crash a cart with a crash-test dummy, belt off and on. Kick a soccer ball on grass, a gym floor, ice, and with no friction.
- **Second Law.** Race fan carts, vary force and mass, predict acceleration with a = F / m, and test it. Includes a data table and graphs.
- **Third Law.** Two skateboarders push off. A balloon rocket carries pennies.

Each station runs predict, test, explain. There is a 10-question check, teacher notes with a standards map, a one-period lesson plan, and an answer key. English and Spanish (EN | ES switch). Two settings, a notebook page and a code-drawn Scott Stadium; the switch in the top bar or the V key changes the setting and nothing else (B flies the camera to the video board, which shows the live numbers). One HTML file, about 1.5 MB. Runs offline in a current browser with mouse, touch, or keyboard. three.js (MIT license) is included inside the file.

File: [`newtons-lab.html`](https://brendanbartanen-svg.github.io/k12-ai-examples/newtons-lab.html)

## Division Brief

Pick any Virginia school division and see nine years of public federal data in five panels: enrollment, students (composition), child poverty, teachers, and revenue and spending per student. Sources: NCES Common Core of Data, U.S. Census Bureau SAIPE, and the NCES/Census F-33 school finance survey. No test scores. One HTML file, about 320 KB.

File: [`division-brief.html`](https://brendanbartanen-svg.github.io/k12-ai-examples/division-brief.html)

## Guardrails

Each page makes no network requests, stores nothing, and runs no AI when it is used. Nothing about a student or user leaves the device.

## Caveats

These are demonstrations, not finished curriculum or official data products.

- The Division Brief's figures were computed by an AI-written script that checks its totals against the federal division files. They have not been checked against Virginia Department of Education reports, and federal counts can differ from state reports.
- Newton's Lab has not been reviewed by a physics teacher or a Spanish-speaking teacher, and it has not been classroom-tested.

## How to use

Open the links above, or download either HTML file and double-click it.

## Contact

Questions can go through [GitHub issues](https://github.com/brendanbartanen-svg/k12-ai-examples/issues) on this repo.

© 2026 Brendan Bartanen, University of Virginia.

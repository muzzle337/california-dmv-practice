# California DMV Practice Center

A lightweight, accessible practice website for the California Class C knowledge test.

## Status
**Foundation only.** The practice question bank and study guide are intentionally pending review. The homepage is usable but exam buttons are disabled until verified content is added.

## Planned features
- Simple study guide prioritizing parking distances, measurements, right-of-way, signs, and other frequently confused rules
- Randomized 35-question mock exams (a study format, not a guarantee of the DMV's current test length)
- Answer explanations and review of missed questions
- In-browser progress saved locally; no account required
- Mobile-friendly design

## Sources and accuracy
Primary content source: [California Driver's Handbook](https://www.dmv.ca.gov/portal/handbook/california-driver-handbook/). Include handbook chapter links in each reviewed question. Independently verify all facts before enabling exams. Do not represent original practice questions as actual DMV test items.

## GitHub Pages setup
Go to **Settings → Pages**, under **Build and deployment** choose **Deploy from a branch**, select **main** and **/(root)**, then save. The expected published address is:
https://muzzle337.github.io/california-dmv-practice/

## Structure
- `index.html` — responsive landing page; no build system required
- `data/questions.json` — question bank placeholder until review

## Disclaimer
Independent educational tool, not affiliated with the California DMV.

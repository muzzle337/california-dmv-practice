# California DMV Coach

Mobile-first California Class C knowledge-test preparation, built for an iPhone 16 Pro Max and other phone screens.

## Current experience (working MVP)
- **Start practicing** opens a 10-question, one-at-a-time coaching round
- **Every answer** shows the correct rule, a simple memory cue, a "how to think about it" prompt, and an official handbook link
- **Mock exam** runs 35 practice questions without immediate feedback; the score and wrong-answer review appear at the end
- **Practice my weak spots** prioritizes previously missed rules
- Progress is saved locally in the browser using `localStorage`; it does not synchronize between devices
- Questions and answer order vary between rounds; the bank currently covers **16 rules / 48 authored question variations** (not a complete DMV curriculum)

## Learning philosophy

Teach **rule recognition**, not memorized phrasing. For example, a parallel-parking question may concern:
1. The **parking-space length** (3 extra feet)
2. The **car-to-car setup gap** (about 2 feet)
3. The **finished curb distance** (within 18 inches)

Explain what the question is really asking, then test the rule in different wordings and situations.

## Key references
- [California Driver's Handbook](https://www.dmv.ca.gov/portal/handbook/california-driver-handbook/)
- [Parking and parallel parking](https://www.dmv.ca.gov/portal/handbook/california-driver-handbook/navigating-the-roads-cont1/)
- [Lane use](https://www.dmv.ca.gov/portal/handbook/california-driver-handbook/navigating-the-roads/)
- [Rules of the road](https://www.dmv.ca.gov/portal/handbook/california-driver-handbook/laws-and-rules-of-the-road-cont1/)

These are original practice questions based on DMV rules, **not actual DMV exam questions**. This early version intentionally prioritizes high-confusion distance and parking questions; broader topic coverage needs to be added before treating the mock score as an indicator of real exam readiness.

## Hosting

On GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save**.
Expected site once published: https://muzzle337.github.io/california-dmv-practice/

No build step or server is required. Open `index.html` directly in a modern browser for local testing.

## Planned improvements
- Expand and independently verify coverage of signs, right-of-way, lane markings, safe driving, and other handbook sections
- Better track performance by topic and ensure diverse question sampling
- Add optional quick study cards before answering new topics
- Test on actual iPhone Safari and audit accessibility/tap behavior

Independent educational app; not affiliated with the California DMV.

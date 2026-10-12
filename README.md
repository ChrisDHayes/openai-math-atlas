# OpenAI Mathematics — Research & Evidence Atlas

An interactive atlas of the 719 AI-generated mathematics manuscripts that OpenAI released on 6 October 2026. It separates what the model **produced**, what the repository **documents**, and what still needs **independent validation** by mathematicians.

**Live site:** https://chrisdhayes.github.io/openai-math-atlas/

- Radial map of 17 fields → 372 research families → 719 manuscripts
- Per-paper dossiers with OpenAI's claim, a labelled "why it may matter" note, Lean source-index linkage# OpenAI Mathematics Atlas — Version 5

## Changes

- Variable radial spoke lengths based on each family's real manuscript count (logarithmic, capped at eight).
- Branch-length control to switch between family-size and original uniform layout.
- Interactive radius guides, legend, and more explicit hover descriptions.
- A less brittle catalogue validation rule: 372 research families and at least 719 manuscripts, with unique URLs and source descriptions; this accommodates the public catalogue growing beyond the original release.
- Fully retains manuscript-level hover, evidence filter, family navigation, and offline snapshot export.

## Important data note

The source file remains authoritative. On page load, the website attempts to load `CONTENTS.md` and `lean/formalization.yaml` directly from the public `openai/math` GitHub repository. If the manuscript catalogue is unavailable, it shows only the original taxonomy and labels the branch-count encoding as unavailable; it does NOT fabricate paper counts or manuscript descriptions. Use the page's import option if the live source cannot be fetched. You can export a self-contained offline HTML snapshot once the source is loaded and validated.

Length communicates publication quantity, not result validity, novelty, significance, or successful Lean verification.
, and validation questions
- Evidence hierarchy, correction record, scholarly debate, and methods
- Light/dark mode and left-hand navigation

Source data loads live from [openai/math](https://github.com/openai/math). Descriptions are OpenAI's claims, not independent verification. Nothing here is a correctness verdict on any paper.

**Author:** Christopher Hayes, CDAIO. Independent academic work for the Boston University MS in Artificial Intelligence. No institutional endorsement by Boston University, OpenAI or AGMAI is implied.

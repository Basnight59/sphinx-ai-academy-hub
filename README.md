# Sphinx AI Academy — Multipage Educational Hub Prototype

**Live site:** https://basnight59.github.io/sphinx-ai-academy-hub/ (GitHub Pages, served from `main`).

Seven responsive static pages: Home, Academy, Sphinx Method, Learning Lab, Reentry Pathway, Research & Legacy, Partners & Delivery.

## Run
Open `index.html` in a browser, or run `python -m http.server 8000` in this directory and visit http://localhost:8000.

Each page is self-contained: its styles and script are inside the page, so any single `.html` file shows fully styled and works on its own, even when it is opened, downloaded or previewed by itself.

**Editing styles or scripts:** the CSS (in `<style>`) and the JavaScript (in `<script>`) are the same in all seven pages. Change them in every page, not just one.

## Included
- Interactive GIGO prompt-quality diagnostic (heuristic, not AI fact checking)
- TTL knowledge check
- Human adjudication ledger saved in browser localStorage
- JSON export of learning record
- Reentry scenario and completion tracker
- Responsive styling, keyboard focus, semantic landmarks

## Not included
No backend, authentication, SCORM runtime/package, real speech-to-text or audio playback, LMS synchronization, server-side persistence, or verified accreditation. These are production integration tasks.

## Content basis
User discussion, plus public pages https://sphinxglobalenterprisescorp.com/ and https://sphinxanalysis.com/ accessed November 11, 2026. Curricula and delivery tracks are proposed prototypes, not representations of currently deployed courses.
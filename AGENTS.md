# AGENTS.md

## Project
Dependency-free browser simulation for customer discovery.

## Purpose
Help a PdM understand the daily decision load of a special support teacher through a fictional, respectful, choice-based experience.

## Working Rules
- Keep the experience local-first: no build step, no external packages, no network calls.
- Avoid portraying children as problems. Focus on constraints, trade-offs, support systems, time pressure, records, and communication.
- Use fictional names and scenarios.
- Do not claim clinical or legal accuracy. Treat this as a discovery/learning prototype that needs review by actual teachers.
- Prefer small, readable changes.
- Before changing the learning/discovery flow, run a Discovery Gate:
  - Which user and Job does this change serve?
  - Is the change for in-the-moment recall, post-session synthesis, or later Codex reuse?
  - Can an existing element be replaced or simplified instead of adding UI?
  - Is the evidence a fictional simulation signal, participant interpretation, or product hypothesis?
  - What next validation would make this stronger?
- If the user has already chosen a direction, implement it, but still preserve the Discovery Gate reasoning in `docs/discovery.md` when the change affects the product experience.

## Verification
- Open `index.html` directly in a browser.
- Check that each scene advances, meters update, choices affect the reflection, reset works, and Markdown copy works.
- Check that text fits on mobile and desktop widths.

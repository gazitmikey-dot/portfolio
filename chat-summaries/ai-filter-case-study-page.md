# AI Filter Case Study Page — Portfolio

**Date:** 2026-05-31

## What we worked on

Built and refined the `ai-filter.html` portfolio case study page for the AI Natural Language Filter feature. The session focused heavily on the writing — sharpening the problem framing, reordering challenges to match the user experience sequence, and making the "vibe-coded prototype vs UX process" contrast the spine of the whole page. Also updated the `/chat-summary` command to save to the project folder when inside a project.

---

## Decisions Made

- **Challenge order finalized:** Challenge 1 = "or" decision + architecture → Challenge 2 = Popover not drawer → Challenge 3 = Generative UI → Challenge 4 = Applied state, history & persistence. This order follows the user experience sequence rather than chronological design order.

- **Challenge 1 and 2 were merged** (the "or" decision and the three-popover architecture) because they were two sides of the same thought — the why and the how.

- **The Problem section** was rewritten to focus on the integration risk (fragmentation: two filter buttons, two apply mechanisms) rather than explaining how the standard filter works.

- **Challenge 1** now opens with the tempting side-by-side idea the backend could support, then rejects it — shorter and more direct.

- **Challenge 2 (Popover vs Drawer):** Removed the Decision callout and tradeoff paragraph; the two comparison cards speak for themselves. Added a short one-line Decision callout instead: "A drawer implies an agent. This is a filter tool."

- **My Role & Context** was rewritten to describe the actual workflow: developer provided a running prototype + markdown requirements file → Michal used Claude Code to explore directions + Figma for pixel-perfect UI design. Redundant context paragraph removed.

- **The "vibe-coded prototype" contrast paragraph** was moved from My Role & Context to the Conclusion where it lands with full weight after the reader has seen all the decisions.

- **Conclusion** rewritten to 3 paragraphs: the integration problem → the "or" as the foundation → specific list of what changed from the prototype, ending with the bold line: **"The AI-coded prototype solved the feature. The UX process solved the experience."**

- **`/chat-summary` command updated** to save inside the current project's `chat-summaries/` subfolder when run from within a project directory, falling back to `/Users/micha/chat_summery/` otherwise.

---

## Open Questions

- Image placeholders still need to be replaced with actual screenshots/Figma exports.
- "More Works" section only links to Findings Platform and Solar — consider adding the AI Filter page to other case studies' More Works sections.

---

## References

- Portfolio page: `/Users/micha/MyPortfilio/ai-filter.html`
- Figma file: https://www.figma.com/design/ssLzJfbuRYEnX17TkLqtk4/NL-filters?node-id=49-6789
- UX decisions doc: `/Users/micha/finding-prototyping/ai-filter/ai-filter-ux-decisions.md`
- Interactive prototype: `/Users/micha/finding-prototyping/ai-filter/index.html`

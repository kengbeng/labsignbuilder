# Notes — Lab Sign Builder

Overview
- Purpose: generate laboratory entrance notices that list hazards, mandatory controls, MAQ and emergency contacts.
- Implementation: single static `index.html` contains all HTML, CSS, JS and embedded images/data URIs. No server or build system needed.

Key details
- Print target: A4 portrait. The app includes print styles for best results and a supplementary page for extended details.
- Accessibility: uses semantic markup and ARIA where appropriate — test after any UI change.
- Data: Form state is local to the browser and can be exported/imported as JSON.

Maintenance checklist
- If expanding features, refactor CSS/JS into separate files and add a lightweight build step (optional).
- Consider adding a visual screenshot for README and a small example JSON data file in `examples/`.

Potential improvements
- Add localization and translations for multi-language environments.
- Add GitHub Pages deployment for hosted demo.
- Provide an option to print only summary or full supplement pages.

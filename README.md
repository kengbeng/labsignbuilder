# Lab Sign Builder

Polished, print-ready laboratory entrance sign generator — a small, self-contained HTML app for creating lab notices and entrance signage.

## Quick summary

Open `index.html` in any modern browser to launch the lab sign builder. The app runs fully client-side (no backend) and outputs print-optimised entrance notices suitable for A4 printing or PDF export.

## Features

- Single-file static app (HTML with embedded CSS/JS and image data URIs)
- Form-driven inputs for laboratory details, hazards, mandatory controls, MAQ and emergency contacts
- Live print preview and print/PDF export
- Supplement page for extended hazard/control details
- Print-optimised layout and accessible markup

## Usage

1. Clone or download the repository and open `index.html` in your web browser.
2. Complete the required fields and select hazards/controls as confirmed by the risk assessment.
3. Preview the generated sign(s) in the right-hand pane.
4. Click the "Print / Save PDF" button to produce a print-ready PDF or print directly.

Printing tips:
- The app uses A4 portrait as the default page size and includes print CSS for accurate pagination.
- Safari and Chromium-based browsers may render print sizes slightly differently — preview before printing.

## Customisation

- Editing `index.html` allows you to change wording, styles, and embedded assets.
- For larger customisations, consider separating CSS and JS into distinct files to simplify maintenance.

## Development & maintenance notes

- Because images and icons are embedded as data URIs, the HTML file is large — consider external assets for iterative development.
- Preserve ARIA attributes and semantic structure when changing layout to maintain accessibility.

## Suggested repo description (one-line)
"Lab Sign Builder — browser-based, print-ready laboratory entrance notice generator (single-file HTML)."

## About (short)
A compact browser tool to generate consistent, print-ready laboratory entrance notices for local use and easy printing.

## Contributing
Small improvements or bug fixes welcome via PR. For larger changes, open an issue to discuss design and accessibility.

## License
Add a LICENSE file or declare a license (MIT recommended for public use).

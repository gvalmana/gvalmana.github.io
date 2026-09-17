# Repository Guidance

## Project shape

- This is a static GitHub Pages site; there is no package manager, build step, test suite, lint configuration, or code generation.
- `index.html` is the main web CV. `cv-pdf.html` and `cv-pdf-en.html` are the print-oriented Spanish and English CV sources; their downloadable artifacts are `Gustavo_Valmana_CV.pdf` and `Gustavo_Valmana_CV_EN.pdf`.
- `scribbler.js` contains the shared navigation, responsive menu, typewriter, and documentation-page behavior.
- `scribbler-global.css`, `scribbler-landing.css`, and `scribbler-doc.css` contain the shared, landing-page, and documentation-page styles respectively.
- `doc.html` is a legacy Scribbler documentation page; change it only when the task explicitly concerns that page.

## Development and verification

- Serve the repository root locally with `python3 -m http.server 8000`, then inspect `http://localhost:8000`.
- There are no repository-provided automated checks; verify changed pages and linked assets through the local server.

## Content and deployment constraints

- GitHub Pages serves the repository root directly. Preserve `CNAME` and relative asset paths when moving or renaming files.
- Keep CV content synchronized across `index.html`, both print sources, both PDFs, and the Spanish/English text resumes when the change affects professional information.
- External fonts and Font Awesome are loaded from CDNs in the HTML files; do not assume they are available offline when validating visual output.

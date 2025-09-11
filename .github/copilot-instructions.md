# Copilot Instructions for This Codebase

## Project Overview
This is a static website project consisting of several HTML pages and associated CSS stylesheets. The site structure is simple and does not use any frameworks or build tools.

### Key Files & Structure
- **HTML files:**
  - `Index.html`: Main landing page
  - `contato.html`, `obrigado.html`, `servicos.html`, `sobre.html`: Additional content pages
- **CSS files:** Located in the `assets/` directory
  - `style.css`: Global styles
  - Page-specific styles: `base.css`, `contato.css`, `obrigado.css`, `servicos.css`, `sobre.css`

## Developer Workflows
- **No build process:** All files are static. Changes to HTML or CSS are reflected immediately in the browser.
- **No automated tests or scripts:** Manual browser testing is required.
- **Debugging:** Use browser developer tools (F12) for inspecting layout, styles, and console errors.

## Project-Specific Conventions
- **File naming:**
  - Page HTML files use lowercase or lowercase with accents (e.g., `Index.html`, `contato.html`).
  - CSS files for each page are named after the page (e.g., `contato.css` for `contato.html`).
- **Styling:**
  - Shared styles go in `style.css` and/or `base.css`.
  - Page-specific styles are in their respective CSS files.
- **No JavaScript:** The project currently does not use any JavaScript files or dynamic client-side logic.

## Integration Points
- **Assets:** All CSS files are loaded from the `assets/` directory. Ensure correct relative paths in HTML `<link>` tags.
- **No external dependencies:** The project does not use npm, package managers, or third-party libraries.

## Examples
- To add a new page:
  1. Create a new HTML file in the root directory.
  2. Optionally create a matching CSS file in `assets/`.
  3. Link the CSS file in the new HTML page using `<link rel="stylesheet" href="assets/[your-css].css">`.

## Recommendations for AI Agents
- Focus on HTML and CSS improvements, accessibility, and responsive design.
- When adding new features, follow the existing file and naming conventions.
- Document any new conventions or workflows in this file for future agents.

---
_Last updated: September 11, 2025_

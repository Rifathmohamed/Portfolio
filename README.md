# Rifath Mohamed — Portfolio

An interactive design portfolio built with semantic HTML, CSS and JavaScript. No package dependencies, account, backend or hosted-site service required.

## Open in VS Code

1. Extract the ZIP into a folder on your computer.
2. Open that folder in VS Code (File → Open Folder).
3. Install the current Node.js LTS release from https://nodejs.org if needed. Restart VS Code after installation.
4. In Terminal → New Terminal, run `node --version` to confirm installation.
5. Run `npm run dev` and open http://localhost:5173.
6. Stop the server with Ctrl+C.

You can also double-click index.html to view the site without Node.js. Clipboard access may be restricted in file mode; localhost is recommended.

## Files

- index.html — page layout, biography, projects, contact links.
- style.css — responsive layout, colours, typography, animation.
- app.js — module data, project stories, dialogs and interactions.
- assets/ — Regoxa product screens and supplied original resume.
- server.mjs — local Node server, bound only to localhost.
- build.mjs — copies the deployable static site into dist/.

Run `npm run build` to prepare a static export. No installation or npm dependencies required.

## Content notes

- Current website title: Engineer — UX/UI Designer at Regami Solutions. The exact promotion date was not supplied; full-time employment begins May 2025, with a note about subsequent promotion.
- Regoxa is credited as team work across Extractor, Classification, Flowra and OXY. The project overview does not invent research results or performance metrics.
- Regoxa screenshots are from public documentation supplied by Rifath. Retain the source links in project detail views.
- Mento's cover is original typographic portfolio artwork, not a recreation of the product UI. It links to the authentic Behance case study because the original screen assets were inaccessible during development. Replace the cover with exported Mento screenshots when available.
- The camera cover is an abstract illustration, not an actual product screenshot.
- Downloadable resume is the original supplied PDF and still uses Junior Engineer. Replace assets/Rifath-Mohamed-resume.pdf with an updated resume before publishing.
- The biography includes editorial copy based on supplied experience; review it before public release.
- Fonts load from Google Fonts when online; local system fallbacks work offline. All product images are bundled.

## Design references

Provided by user: Oorja Kapoor, Aaron Carvalho, Lehar Sindra, Sanjay Menon via Wall of Portfolios. Aaron's live site was unavailable during review. The implementation is original; reference assets and copy were not reused.

## Image sources

- https://demo-docs.regoxa.com/img/extractor/Extractor_LiveCapture.png
- https://demo-docs.regoxa.com/img/spendAnalyser/SpendAnalyserPage.png
- https://demo-docs.regoxa.com/img/mercury/MercuryPage.png
- https://demo-docs.regoxa.com/img/oxy/oxyopen.png

## Accessibility

Includes semantic sections, a skip link, visible focus states, native modal dialogs with Escape dismissal, keyboard-movable notes, selected-state announcements, reduced-motion support and touch layouts. Test with your preferred screen reader before public release.

## Interactive workspace (version 2)

- Open any project directly from the canvas cards.
- Drag cards by their top handles on desktop, or focus the handle and use arrow keys.
- Tidy up arranges the cards; Spread out restores the expressive layout.
- Shuffle changes card positions and angles; Reset restores their defaults.
- Colour controls change the canvas accent.
- Ctrl+K / Cmd+K opens searchable navigation. Use arrow keys and Enter to choose.
- Regoxa's project window includes four module chapters and expandable screenshots.
- Previous/next controls let visitors browse projects within the explorer.
- On phones, cards use a touch-friendly flow instead of free dragging.
- Reduced-motion settings disable decorative animation and cursor labels.

Verified in headless Chromium at 1440px desktop and 390px mobile widths: no JavaScript errors, no mobile horizontal overflow, and no broken image sources. Tested project navigation, module chapters, screenshot zoom, Escape dismissal, canvas layout/reset, keyboard dragging, command search, and colour controls. Desktop, mobile and project-window screenshots were visually reviewed.


Public release: direct email and resume download are omitted pending explicit publication approval. Enable GitHub Pages using main branch, / (root).

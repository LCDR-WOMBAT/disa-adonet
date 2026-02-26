# disa-adonet
# DISA Adonet (disa-adonet)

A small static website/repository containing standalone HTML pages. This repo stores a few prototype/site pages that can be viewed locally or hosted as a static site (for example, via GitHub Pages).

Overview
- Repository owner: LCDR-WOMBAT
- Primary files in this repo:
  - index.html — main entry page
  - darkmyst.html — standalone page (theme/name: darkmyst)
  - agora-comms.html — standalone page (agora communications)
  - dgcs-adonis.html — expected page (see note below)
  - LICENSE — repository license

Project summary
This repository is a collection of static HTML pages that together form a small site or set of prototypes. The pages are self-contained and can be opened directly in a browser or served using a lightweight static server. Use this repo to preview the pages locally, iterate on HTML/CSS/JS, or deploy as a simple static site.

Quick start — view locally
1. Clone the repo
   git clone https://github.com/LCDR-WOMBAT/disa-adonet.git
2. Open the site directly:
   - Open disa-adonet/index.html in your browser (double-click or use your browser's File > Open).
3. Or serve with a simple HTTP server (recommended to avoid cross-origin issues):
   - Python 3:
     python -m http.server 8000
     Then open http://localhost:8000/ in your browser.
   - Node (http-server):
     npm install -g http-server
     http-server .
     Then open the printed local URL.

Files and intent
- index.html — entry page; link or redirect to other pages as appropriate.
- darkmyst.html — theme or demo page named "darkmyst".
- agora-comms.html — page related to "agora communications".
- dgcs-adonis.html — intended to be part of this repo per instructions; currently not present (see note).
- LICENSE — license file; see it for reuse and distribution terms.

Deployment
- GitHub Pages (recommended for static hosting)
  1. In the repository Settings > Pages, set the source to branch: main (or main branch root).
  2. The site will be published at https://LCDR-WOMBAT.github.io/disa-adonet/ (once enabled).
- Alternative: deploy to any static host (Netlify, Vercel, S3, etc.) by pointing to the repository root.

Contributing
- Contributions are welcome. Typical workflow:
  1. Fork the repository.
  2. Create a branch for your change.
  3. Make changes and test locally.
  4. Submit a pull request describing the change.
- Keep changes to HTML/CSS/JS isolated and include screenshots or a brief demo description when appropriate.

Notes and next steps
- I inspected the repository contents and confirmed index.html, darkmyst.html, and agora-comms.html are present.
- dgcs-adonis.html was mentioned as a required file but I did not find it in the repository. Would you like me to:
  - create a placeholder dgcs-adonis.html (basic template) and add it to the repo, or
  - skip creating it and only update README.md?
- If you want, I can auto-fill additional sections (usage examples, page descriptions, screenshots) or commit the README.md (and optional dgcs-adonis.html placeholder) directly to the repository. To commit files I will need your confirmation to push to LCDR-WOMBAT/disa-adonet.

License
See LICENSE in the repository for full license text.

Contact
Repository owner: LCDR-WOMBAT
(If you'd like a different author or contact block added, tell me what to include.)

GitHub Copilot Chat Assistant

Would you like me to:
- commit this README.md into LCDR-WOMBAT/disa-adonet now?
- create and commit a placeholder dgcs-adonis.html (and, if so, any content you want in it)?
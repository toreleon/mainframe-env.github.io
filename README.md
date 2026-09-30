# mainframe-env project site

Independent introduction site for [toreleon/mainframe-env](https://github.com/toreleon/mainframe-env).

Live site: https://toreleon.github.io/mainframe-env/

Source repository: https://github.com/toreleon/mainframe-env.github.io

## Preview

Run `python3 -m http.server 4173` in this checkout and open `http://localhost:4173`.
The site uses plain HTML, CSS, and JavaScript. No build or package installation is required.

## Publishing

The primary site is hosted from the `mainframe-env/` directory on the `main`
branch of [toreleon/toreleon.github.io](https://github.com/toreleon/toreleon.github.io).
Copy `index.html`, `styles.css`, `script.js`, and `assets/` from this source
repository into that directory to publish updates, then confirm the Pages
deployment succeeds. Preserve the hosting repository's other content.
All asset paths are relative so both organization and project Pages URLs work.

The original repository-root Pages address remains available; its canonical
metadata points to the primary site above.

## Content authority

Project facts were checked against the project README, architecture overview,
coverage roadmap, and GitHub latest-release API on 2026-09-30. The published release
is 0.8.2 (source bundle), the development baseline is 0.8.3, and 0.9.0 is planned.
Update the release band, project status, and quick start together when these change.
Subsystem descriptions identify project boundaries; they do not claim complete
IBM coverage, production readiness, or licensed equivalence.

## Design

Technical landing page using native CSS, locally hosted IBM Plex Sans and Mono,
graphite surfaces, a single green accent, and square corners. The hero diagram
explains functional architecture, rather than depicting a runtime screenshot.
Tabs support arrow keys, Home, End, and a no-JavaScript documentation fallback.
Clipboard failure selects the command text and explains how to copy it manually.
Motion respects `prefers-reduced-motion`.

Font license notices are retained in `assets/fonts/`. Website source is Apache-2.0.

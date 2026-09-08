# replaycut.de

The website for [replaycut](https://github.com/KallistoX/replaycut), a clip
manager for the OBS replay buffer.

One static page plus a privacy policy and an Impressum. No framework, no build
step, no external fonts and no tracking: `index.html`, `styles.css`, `assets/`.
Colours, spacing and type come from the app's design tokens
(`docs/design/tokens.css` in the main repository), so the site and the program
look like the same thing.

The download button links to the latest release and, when the browser can reach
the GitHub API, fills in version, size and date; without JavaScript it stays a
plain link to the releases page.

Served by GitHub Pages from `main`. Edit, commit, push - that is the deployment.

# Mooncraft project website

[Visit the website](https://monk-eee.github.io/mooncraft-site/).

Public presentation for Mooncraft, a lunar RTS prototype built with Rust and
Bevy and a proving ground for dependable agent-development tooling.

## Publication boundary

This repository contains only the public website and its approved logo.
The game source, internal documentation, work records and runtime assets remain
in the separate private `monk-eee/Mooncraft` repository. Links to that repository
require access; they do not make its contents public.

Do not copy private project files into this repository. The Pages workflow
uploads only `index.html` and `assets/mooncraft_logo.png`, not the checkout.

## Editing and preview

- Edit `index.html`; styles and the small system-theme detection script are
  inline. There is no package installation, application build or external font.
- The page follows the system light/dark preference. Use `?scoutTheme=light` or
  `?scoutTheme=dark` to preview either theme explicitly.
- Keep prototype status, platform qualification and implemented/planned features
  distinct. Artwork is not evidence that a unit is playable.
- Use a local static web server to preview the page and its relative image path.
  No browser-playable game is hosted here.

## Deployment

GitHub Pages uses GitHub Actions. Push changes to `main`, or manually run
**Deploy project website**. The workflow stages an explicit allowlist of public
files before upload and deploys with GitHub's short-lived Pages credentials.
There is no cross-repository access token and no access to the private game.

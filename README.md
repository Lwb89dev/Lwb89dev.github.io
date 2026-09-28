# github-page

Source for the personal GitHub Pages site — a short recap of the projects
across [Lwb89dev](https://github.com/Lwb89dev) and
[roadstrapp](https://github.com/roadstrapp), and the philosophy behind them
(FOSS licensing, de-Google, data sovereignty, device control, Bitcoin &amp; Nostr).

Plain HTML/CSS/JS, no build step, no dependencies, no external requests.

## Publish it

1. Push this repo to GitHub.
2. Repo Settings → Pages → Build and deployment → Deploy from a branch.
3. Branch: `main`, folder: `/ (root)`.

If this repo is named `<username>.github.io`, GitHub serves it at the root
domain automatically. Otherwise it's served under `/<repo-name>/` — update
any absolute links in `index.html` if you rely on that path.

## Update the project list

Repo cards in `index.html` are written by hand (name, description, license,
stars) rather than fetched at runtime, to keep the page dependency-free and
fast. Re-sync them manually when a repo changes.

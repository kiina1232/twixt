# TwixT Online

Browser-only TwixT game for GitHub Pages.

## Features

- CPU match with 5 levels.
- Friend match through WebRTC offer/answer codes.
- No backend server, database, paid API, or build step.
- `index.html` works as the GitHub Pages entry file.

## Free GitHub Pages Setup

1. Create a public GitHub repository.
2. Put `index.html`, `README.md`, and `.nojekyll` in the repository root.
3. Open the repository's `Settings` > `Pages`.
4. Set `Build and deployment` to `Deploy from a branch`.
5. Select `main` and `/root`, then save.
6. Open `https://<your-user-name>.github.io/<repository-name>/`.

GitHub Free supports GitHub Pages for public repositories. This project only uses static HTML/CSS/JavaScript, so it does not need paid hosting.

## Local Play

Open `index.html` in a browser. CPU match works locally. For friend match and clipboard behavior, GitHub Pages over HTTPS is the easiest target.

## Notes

The CPU is a lightweight in-browser evaluator, not a perfect solver. Levels increase by adding tactical checks, link and component scoring, and shallow reply search.

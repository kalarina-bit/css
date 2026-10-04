# css

GitHub-style themes for **Gitea 1.27.x** — light and dark, built with modern CSS (`color-mix()`), matching GitHub's typography, spacing and color tokens.

<p align="center">
  <img src="assets/preview-2.jpg" width="100%" alt="Theme preview">
</p>

<p align="center">
  <img src="assets/preview-1.png" width="160" alt="css">
</p>

## Themes

| File | Description |
|---|---|
| [`css/theme-light.css`](css/theme-light.css) | GitHub Light — for `prefers-color-scheme: light` |
| [`css/theme-dark.css`](css/theme-dark.css) | GitHub Dark — for `prefers-color-scheme: dark` |
| [`css/theme-auto.css`](css/theme-auto.css) | Switches between the two automatically based on system preference |

## Requirements

A browser with `color-mix()` support: Chrome 111+, Firefox 113+, Safari 16.2+.

## Installation

1. Copy the files from [`css/`](css/) into your Gitea instance's `custom/public/assets/css/` directory (or wherever your Gitea deployment serves custom CSS from).
2. Reference `theme-auto.css` (or `theme-light.css` / `theme-dark.css` directly) from your Gitea custom template, or set it as a selectable theme in `app.ini`.
3. Restart Gitea, or reload the page, to pick up the new styles.

## License

Use and adapt freely.

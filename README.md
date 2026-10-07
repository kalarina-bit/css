# css

GitHub-style themes for **Gitea** — light and dark,  matching GitHub's typography, spacing and color tokens.

<p align="center">
  <img src="assets/preview-2.jpg" width="100%" alt="Theme preview">
</p>



## Themes

| File | Description |
|---|---|
| [`css/theme-light.css`](css/theme-light.css) | GitHub Light — for `prefers-color-scheme: light` |
| [`css/theme-dark.css`](css/theme-dark.css) | GitHub Dark — for `prefers-color-scheme: dark` |
| [`css/theme-auto.css`](css/theme-auto.css) | Switches between the two automatically based on system preference |

## Installation

1. Copy the files from [`css/`](css/) into your Gitea instance's `custom/public/assets/css/` directory (or wherever your Gitea deployment serves custom CSS from).
2. Reference `theme-auto.css` (or `theme-light.css` / `theme-dark.css` directly) from your Gitea custom template, or set it as a selectable theme in `app.ini`.
3. Restart Gitea, or reload the page, to pick up the new styles.

## License

Released under the **MIT License** — see the [LICENSE](LICENSE) file. You may use, modify and redistribute the themes, including in commercial Gitea instances, as long as the copyright notice is kept.

The color values follow GitHub's [Primer](https://github.com/primer/primitives) design tokens, © GitHub Inc., also MIT-licensed. This project is not affiliated with or endorsed by GitHub or Gitea.

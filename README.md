# hosspro.com

Personal site for Hossein Rezai, served by GitHub Pages at
[www.hosspro.com](https://www.hosspro.com/).

Plain static HTML — no build step, no framework. Open `index.html` directly, or
serve the directory with `python3 -m http.server` to check relative paths.

| Path            | What it is                                                     |
| --------------- | -------------------------------------------------------------- |
| `index.html`    | The whole page. Content and layout live here as inline styles.  |
| `styles.css`    | Design-system tokens and component classes (`card`, `tag`, `blueprint`, `duotone`). |
| `assets/`       | Portrait image.                                                  |
| `papers/`       | Published papers, linked from the Publications section.          |
| `CNAME`         | Custom domain. Removing this file unsets the domain on the next deploy. |

Pages deploys the default branch from the repository root.

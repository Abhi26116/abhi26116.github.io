# abhi26116.github.io

Support and privacy pages for my iOS apps, served by GitHub Pages at
https://abhi26116.github.io/.

| App | Support | Privacy policy |
| --- | --- | --- |
| Coffee to IPO (was Startup Merge) | [/startup-merge/support.html](https://abhi26116.github.io/startup-merge/support.html) | [/startup-merge/privacy.html](https://abhi26116.github.io/startup-merge/privacy.html) |
| Stitch Story | [/stitch-story/support.html](https://abhi26116.github.io/stitch-story/support.html) | [/stitch-story/privacy.html](https://abhi26116.github.io/stitch-story/privacy.html) |

## Adding an app

1. Copy the `startup-merge/` folder to a new folder named after the app
   (lowercase, words joined by `-`).
2. Replace the icon and edit the three pages for the new app.
3. Add a card for it in `index.html` and a row in the table above.

Coffee to IPO keeps the `startup-merge/` folder from its first name, because
App Store Connect and the app link to those URLs.

All pages share `style.css` at the root. `.nojekyll` tells GitHub to serve the
files as they are.

Stitch Story also has `stitch-story/terms.html` and serves its downloadable picture albums from
`stitch-story/content/` (`manifest.json`, `remote_config.json`, `packs/`), copied from the game's
`RemoteContent/` folder; the game reads them from `https://abhi26116.github.io/stitch-story/content/`.

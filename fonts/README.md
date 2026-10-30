# Fonts used by the pages in `docs/`

The privacy page (`privacy.html`) uses the brand fonts from the brand guide, served from this folder so the page makes no third-party font request.

| File | Face | Use | Licence |
|---|---|---|---|
| `ElMessiri-Bold.ttf` | El Messiri, weight 700 | Headings, +10 tracking (`letter-spacing:.01em`) | SIL Open Font License 1.1 |
| `Arimo-Regular.ttf`, `Arimo-Bold.ttf` | Arimo 400 / 700 (Latin subset) | Body text | SIL Open Font License 1.1 — `OFL.txt` |

These are the same files as `app/src/main/res/font/`. Arabic body text falls through to the reader's system Arabic face, because Arimo has no Arabic.

When the page is published to the `hisba-privacy` repo, copy this `fonts/` folder alongside `privacy.html` (as `index.html`).

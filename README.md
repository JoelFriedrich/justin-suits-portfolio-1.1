# Justin Suits — Portfolio

Single-page portfolio site for Justin Suits: voice actor, narrator, poet.

Exported from a Claude Design canvas.

## Files

| Path | Purpose |
| --- | --- |
| `Justin Suits.dc.html` | The page itself — markup, inline styles, and the interactive `x-dc` components |
| `support.js` | `dc-runtime` — renders the `<x-dc>` components (loads React/Babel from unpkg at runtime) |
| `assets/hero.jpg` | Hero background |
| `assets/about.jpg` | About section portrait |
| `assets/poetry.jpg` | Poetry section photo |

Fonts (Courier Prime, EB Garamond) load from Google Fonts.

## Running locally

The page uses relative paths, so open it through a web server rather than `file://`:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000/Justin%20Suits.dc.html

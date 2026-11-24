# Cartas digitales

Public digital menus for restaurants, served via GitHub Pages.

## Structure

- `index.html` — landing page listing all published menus.
- `<slug>/index.html` — one static page per restaurant (e.g. `cafe-bar-central/`).
- `qr/` — QR code images linking to each published menu.
- `.nojekyll` — serve files as-is, no Jekyll processing.

Each menu is reachable at `https://wertymsd.github.io/cartas/<slug>/`.

## Menus

| Restaurant | Location | Page |
| --- | --- | --- |
| Café Bar Central | Chiclana de la Frontera (Cádiz) | [cafe-bar-central](https://wertymsd.github.io/cartas/cafe-bar-central/) |

## Adding a restaurant

Create `<slug>/index.html` as a self-contained static page, add it to the
landing list above, publish, then generate a QR code into `qr/<slug>.png`
pointing to the final URL.

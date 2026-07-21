# AfterShip Landing Page

Static implementation of the "AfterShip Landing - Desktop & Mobile" design (paid-search demo-request page).

## Structure

- `index.html` — the page markup
- `assets/css/tokens.css` — design tokens (colors, type scale) and base styles
- `assets/img/` — logos and product screenshots

## Run locally

```
python3 -m http.server 8000
```

Then open `http://localhost:8000/index.html`.

The demo request form embeds a HubSpot form (portal `19866549`) and requires network access to `js.hsforms.net` to render.

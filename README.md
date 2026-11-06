# apps

Small web apps, published with GitHub Pages at **https://maorkavod.github.io/apps/**.

## Structure

```
index.html      # hub page – lists every app from apps.json
apps.json       # the list of apps (path, title, description, icon)
workout/        # "אימון יומי" – daily workout app
  index.html
  man.js        # 3D human model (glTF, base64)
```

## Adding a new app

1. Create a folder, e.g. `my-app/`, with an `index.html` inside.
2. Add an entry to `apps.json`:

```json
{ "path": "my-app/", "title": "My app", "description": "What it does", "icon": "🧩" }
```

The hub page picks it up automatically.

## Credits

- 3D rendering: [three.js](https://threejs.org) (loaded from jsDelivr).
- 3D character: the Ready Player Me sample avatar from the three.js examples, restyled with sportswear.

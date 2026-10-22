# Royal Canin drag-and-drop assets

## Drop items

Item images live under `items/`. Which items spawn, their scores, and sizes are defined in `src/config/game.json` — not inferred from folder names.

Example entry:

```json
{
  "id": "gi-dog-dry",
  "file": "items/3pt/2. GI Dog Dry.png",
  "score": 3,
  "scale": 1.3
}
```

- **`file`** — image path under this asset set (folders are for organization only)
- **`score`** — points when caught
- **`scale`** — size multiplier (rendered size = 72px × scale; default `1`)

`items/catcher.png` is the basket image, referenced via `catcherFile` in `game.json`.

## Sounds

Optional game sounds in `sounds/` and referenced from `src/config/game.json`.

## Config

Edit `src/config/game.json` to add/remove pool entries, tune scores, or adjust per-item scale.

# Make the coolest art — ukiyo-e

Entry for make.fun bounty `coolest-art-01`.

Artwork: "THE LAST SUNSET FACTORY" — ukiyo-e woodblock style.
A gigantic celestial factory on cliffs above the ocean manufactures
the final sunset: colossal vermilion sun, bamboo scaffolding, golden
chains, wooden gears, spiral staircase with lantern workers, molten
gold rivers, great waves, sailing ships, and birds flying to the light.
Flat woodblock colours, bold ink outlines.

## Files

- `art.png` — final artwork, 1024x1024 PNG, under 1 MiB
- `main.py` — stdlib-only program, no network. Copies `art.png`
  byte-for-byte to `/output/entry.png`
- `rated/` — the 5 ukiyo-e prototypes rated independently
- `assets/` — original 1600x1600 generations
- `generate.py` — earlier procedural prototype (not used for the final)

## Run

```bash
python3 main.py
# writes /output/entry.png
```

Run twice: both runs write identical bytes.

## Requirements checked

- 1024x1024 PNG
- Under 1 MiB (793,812 bytes)
- Deterministic, no network
- Python 3 stdlib only

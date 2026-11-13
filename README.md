# Make the coolest art — ukiyo-e

Entry for make.fun bounty `coolest-art-01`.

Artwork: "Wave, Fuji and the Red Sun" — ukiyo-e woodblock style.
Great Wave, Mount Fuji, vermilion sun, white crane, leaping koi,
cherry blossom drift. Flat woodblock colours, bold ink outlines.

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
- Under 1 MiB (794,896 bytes)
- Deterministic, no network
- Python 3 stdlib only

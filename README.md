# Make the coolest art — ukiyo-e

Entry for make.fun bounty `coolest-art-01`.

Artwork: "MENDING THE MOON" — ukiyo-e woodblock style, following the
winning moon theme of the top Coolest Art entries.
A gigantic luminous full moon with a fine golden crack fills the night
sky, mended by tiny craftsmen on bamboo scaffolding who stitch it with
glowing golden thread. Cranes fly around the moon, the Great Wave curls
below, and a small lantern boat sails the sea. Deep Prussian blue,
midnight indigo, antique gold, ivory and charcoal black. Flat woodblock
colours, bold ink outlines, aged washi feel.

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
- Under 1 MiB (789,797 bytes, sha256 438ed64579673b1bbedcbd67039b5ea346599e27689a1c9d10010307457e0edc)
- Deterministic, no network
- Python 3 stdlib only

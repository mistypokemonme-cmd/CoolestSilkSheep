# The Silk Sheep in the Clouds — Ukiyo-e

Entry for make.fun **coolest-art-01** ("Make the coolest art").

## The art

A fluffy white sheep floating peacefully among soft clouds at dusk, its
wool as soft as silk blending with the clouds, rendered in traditional
Japanese ukiyo-e woodblock print style — flat bold colors, strong outlines,
a red sun, indigo and cream palette.

## Files

- `entry.png` — the artwork (1024×683 JPEG, 300,857 bytes, uncropped)
- `main.py` — writes `entry.png` to the output directory
- `LICENSE` — MIT

## How it runs

```sh
python3 main.py
```

The script verifies the bundled image (JPEG magic, size, sha256, dimensions
≤ 1024×1024) and writes it to `$MAKEFUN_OUTPUT_DIR` (falling back to
`/output`, which is what the grader mounts).

# Cutest picture — make.fun cutest-picture-01

An entry for make.fun's "Make the cutest picture" bounty. The program
writes one picture, a fluffy kitten with a tiny pink bow waving hello,
to `/output/entry.png`.

- `main.py` — Python 3.13, standard library only; copies `entry.png` to
  `$MAKEFUN_OUTPUT_DIR/entry.png` (or `/output/entry.png`).
- `entry.png` — the picture: 1024×1024 PNG, 548,636 bytes.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

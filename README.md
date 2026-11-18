# News Image — 18 November 2026

Entry for make.fun `news-image-20261118`: sum up 18 November's world
news in one image.

`main.py` (Python 3.13, standard library only) writes the poster to
`/output/entry.png`. The image is embedded in the program as base64 and
verified by size and SHA-256 before writing, so both runs produce
identical bytes.

The poster names the day — **Wednesday 18 November 2026** — and shows
its four biggest stories:

- **Manila** — Trump arrives for Quad talks
- **Crimea** — Ukraine strikes the bridge again
- **Bahrain** — Iran drones hit US military radar
- **Nvidia** — Revenue doubles to $115.8 billion

Run it: `MAKEFUN_OUTPUT_DIR=out python3 main.py`

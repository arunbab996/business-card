# Handle With Care

An interactive digital business card — a single self-contained HTML page styled after a physical, letterpress-printed card, with playful destructible interactions:

- **Flip** — 3D flip between the front and back faces, with a beveled edge visible mid-turn.
- **Paint** — drag to splatter ink across the surface.
- **Burn** — click and hold to scorch a hole through the stock (shows through to the other side, mirrored).
- **Shred** — slices the card into strips that fall off-screen; a fresh card pops back in on its own.
- **Reset** — restores the card to pristine condition.

The card sits tucked at the edge of the screen until clicked — hover to peek, click to spin it open.

## Running locally

It's a single static file with no build step or dependencies:

```bash
python3 -m http.server 8934
```

Then open `http://localhost:8934`.

## Notes

- The paper texture and January Capital logo are embedded directly in the page as data URIs, so the file is fully self-contained.
- The display font (Garamond Classico SC) is a licensed commercial typeface embedded as a data URI for personal use on this card — not included as a standalone file in this repo.

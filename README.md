# PRAVA Quotes — OptiSigns Slideshow

Self-contained HTML slideshow for in-office OptiSigns screens.

- `index.html` — shows 3 random PRAVA quotes per load, 10 seconds each, fullscreen on black. All 51 quote images are embedded (base64), so no external image hosting is needed.

## Hosting (GitHub Pages)
Enable Pages: Settings → Pages → Deploy from branch → main → /root. Live URL:

    https://YOURNAME.github.io/REPO/

## Embed in OptiSigns (iframe)
    <iframe src="https://YOURNAME.github.io/REPO/" width="1920" height="1080" frameborder="0" style="border:0;" allowfullscreen></iframe>

## Editing
- Quotes per play: edit `SLIDE_COUNT` in index.html
- Timing: edit `SLIDE_MS` (milliseconds)
Then commit + push; the live screen updates within ~1 minute.

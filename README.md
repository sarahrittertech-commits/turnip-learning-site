# Turnip Learning — landing page

A one-page site for the Turnip Learning app, modeled on the
[Bike Brevard Map site](https://github.com/sarahrittertech-commits/bike-brevard-site).

Plain HTML and CSS: no framework, no build step, no analytics, no tracking,
and no requests to any other site (the fonts are hosted here too).

```
index.html     the whole page
styles.css     all styling (colors and fonts from docs/brand/turnip-brand-guide.md)
fonts/         Fraunces + DM Sans, latin subset (SIL Open Font License)
img/           Turnip mascot and icons
shots/         app screenshots (from design/v0)
```

## Preview it on your Mac

```bash
python3 -m http.server 8770
```

Then open http://127.0.0.1:8770 in a browser.

## Still to fill in

Sections waiting for Sarah's own words are marked twice: an HTML comment
starting `TODO (Sarah)` and a dashed box on the page (class `todo`).
Replace the box with real paragraphs and delete the comment.

- The original idea, and why it's called Turnip
- The first version (2018) and the versions in between
- What rebuilding it with Claude was like

## Swap later

- **Mascot:** `img/turnip.png` is recolor study 2 (white root). Replace it
  once the final mascot is picked (design/mascot-recolor).
- **Screenshots:** `shots/` shows the September design. Replace them after
  the redesign, at 414 × 900.

## When Apple approves the app

The "Coming to iPhone and iPad" button and status line appear twice, between
`<!-- APP STORE LINK (1 of 2) -->` and `<!-- APP STORE LINK (2 of 2) -->`
comments. Replace each with a real `<a class="store-btn" href="…">` link,
the same way as the Bike Brevard site's README describes.

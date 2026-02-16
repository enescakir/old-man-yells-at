# Old Man Yells At \<X\>

Generate custom "Old Man Yells At" Slack emoji. Upload a logo, get a 128x128 PNG with Grandpa Simpson yelling at it.

## Usage

1. Serve the files with any HTTP server:
   ```
   python3 -m http.server
   ```
2. Open `http://localhost:8000`
3. Upload a logo image (drag & drop or click)
4. Enter a name
5. Click **Download** — saves as `old-man-yells-at-<name>.png`

## How it works

- 128x128 canvas (Slack emoji size)
- Your image is drawn in the upper-left area
- The old man template is drawn on top, so his arm overlaps the logo
- Exported as PNG via Canvas API

## Files

- `index.html` — the entire app (HTML + CSS + JS, no dependencies)
- `old-man-yells-at.png` — the Grandpa Simpson template image

# Old Man Yells At \<X\>

Generate custom "Old Man Yells At" Slack emoji. Upload a logo, get a 128x128 PNG with the old man yelling at it.

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

## Examples

| | | | | | | |
|---|---|---|---|---|---|---|
| ![ubicloud](examples/old-man-yells-at-ubicloud.png) | ![claude](examples/old-man-yells-at-claude.png) | ![github](examples/old-man-yells-at-github.png) | ![microsoft](examples/old-man-yells-at-microsoft.png) | ![aws](examples/old-man-yells-at-aws.png) | ![chatgpt](examples/old-man-yells-at-chatgpt.png) | ![copilot](examples/old-man-yells-at-copilot.png) |
| :ubicloud: | :claude: | :github: | :microsoft: | :aws: | :chatgpt: | :copilot: |
| ![gcp](examples/old-man-yells-at-gcp.png) | ![heroku](examples/old-man-yells-at-heroku.png) | ![hetzner](examples/old-man-yells-at-hetzner.png) | ![k8s](examples/old-man-yells-at-k8s.png) | ![postgresql](examples/old-man-yells-at-postgresql.png) | ![ruby](examples/old-man-yells-at-ruby.png) | ![weather](examples/old-man-yells-at-weather.png) |
| :gcp: | :heroku: | :hetzner: | :k8s: | :postgresql: | :ruby: | :weather: |

## Files

- `index.html` — the entire app (HTML + CSS + JS, no dependencies)
- `old-man-yells-at.png` — the old man yelling template image

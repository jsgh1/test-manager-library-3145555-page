# Manager Library — Public presentation page (T-23)

Static, responsive marketing/presentation website for small libraries. **No authentication, no network requests to the API, and no backend dependency.**

## Run

Open `index.html` in any browser, or serve the directory with `python -m http.server 8080`. The page requires no build tools or environment secrets.

## Verify

- Inspect at 375px mobile and 1440px desktop widths.
- Navigate via local page anchors.
- Disconnect or stop the backend; the page still renders and all static links work.
- No member information, admin panel or API bearer token is exposed.

Font loading optionally uses Google Fonts; the local fallback font works offline.

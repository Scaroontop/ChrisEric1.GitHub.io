# Discord Bot Client (Archive)

This repository now serves a simple, static GitHub Pages site from the repository root.
The landing page is intentionally informational and does **not** request Discord credentials or bot tokens.

## Project links

- Latest releases: https://github.com/ChrisEric1/ChrisEric1.GitHub.io/releases/latest
- Chromium extension package: https://chriseric1.github.io/extension.zip
- Firefox extension package: https://chriseric1.github.io/extension.xpi

## GitHub Pages configuration

Use these settings in GitHub:

- **Branch:** `old` (or whichever branch contains this static site)
- **Folder:** `/ (root)`
- Keep `.nojekyll` enabled so files are served directly without Jekyll processing.

## Local testing (no build required)

From the repository root:

```bash
python3 -m http.server 8080
```

Then open:

- `http://localhost:8080/` (homepage)
- `http://localhost:8080/login` (should show fallback, not a blank page)

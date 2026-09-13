# Socialmedia Uploader Web — operations

## Purpose

This static GitHub Pages site provides the official homepage, Terms of Use and
Privacy Policy required by the Socialmedia Uploader application's official API
integrations. It does not contain or run the uploader.

## Publishing flow

1. Edit the static HTML locally.
2. Verify links and confirm that no secret or personal media is present.
3. Publish through a reviewed branch and Pull Request.
4. Confirm GitHub Pages still serves the existing public URLs.

## Files

- `index.html` — public homepage and application summary.
- `terms.html` — conditions for personal use.
- `privacy.html` — local processing and third-party API disclosure.
- `assets/app-icon.png` — public application icon.
- `tiktokivHPvYM0eG7Ek1LyFlAtf7LCifp4M5Wy.txt` — public TikTok URL-prefix ownership signature.

## Boundary

The site does not receive credentials, tokens, uploaded videos, captions or
analytics. Runtime secrets remain on the authorized local computer and are
never committed. The repository name stays `socialmedia-uploader` to avoid
breaking public URLs; only the local folder uses the clearer
`Socialmedia-Uploader-Web` name.

# Socialmedia Uploader Site — operations

## Purpose

This static GitHub Pages site provides the official homepage, Terms of Use and
Privacy Policy required by the Socialmedia Uploader application's official API
integrations. It does not contain or run the uploader.

## Publishing flow

1. Edit the static HTML in `SOCIALMEDIA/SOCIALMEDIA_uploader_site`.
2. Verify links and confirm that no secret or personal media is present.
3. Publish the change through a reviewed branch and Pull Request in
   `lahosjesse/SOCIALMEDIA`.
4. Deploy this directory to the legacy `lahosjesse/socialmedia-uploader`
   GitHub Pages repository without treating that deployment target as an
   independent source project.
5. Confirm GitHub Pages still serves the existing public URLs.

## Files

- `index.html` — public homepage and application summary.
- `terms.html` — conditions for personal use.
- `privacy.html` — local processing and third-party API disclosure.
- `assets/app-icon.png` — public application icon.
- `tiktokivHPvYM0eG7Ek1LyFlAtf7LCifp4M5Wy.txt` — public TikTok URL-prefix ownership signature.

## Boundary

The site does not receive credentials, tokens, uploaded videos, captions or
analytics. Runtime secrets remain on the authorized local computer and are
never committed. The legacy Pages destination keeps the name
`socialmedia-uploader` only to avoid breaking public URLs. All source changes
originate in `SOCIALMEDIA_uploader_site` inside the `SOCIALMEDIA` repository.

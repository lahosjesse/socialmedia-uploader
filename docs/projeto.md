# Socialmedia Uploader public site

**Version:** 1.0.0

## Purpose

This static GitHub Pages site provides the official homepage, Terms of Use, and Privacy Policy required to configure the Socialmedia Uploader application with official social-media APIs.

## Publishing flow

1. Edit the static HTML locally.
2. Verify links and confirm that no secrets or personal media are present.
3. Commit and push normally to `main`.
4. GitHub Pages publishes the repository root.

## Files

1. `index.html` — public homepage and application summary.
2. `terms.html` — conditions for personal use of the uploader.
3. `privacy.html` — disclosure of local processing and third-party API use.
4. `assets/app-icon.png` — public application icon.

## Security boundary

The site is static. It does not receive credentials, tokens, uploaded videos, captions, or analytics. Runtime secrets remain only on the authorized local computer and are never committed to Git.

# Socialmedia Uploader Site

Public website and legal pages for **Socialmedia Uploader**. This directory is
a component of the `SOCIALMEDIA` repository and is the source of truth for the
site. It does not execute uploads; the runtime lives in the sibling directory
`../SOCIALMEDIA_uploader`.

## Project structure

- `index.html` — public application homepage.
- `terms.html` — Terms of Use.
- `privacy.html` — Privacy Policy.
- `assets/` — public visual assets.
- `docs/OPERATIONS.md` — publishing flow and repository boundary.
- `docs/CHANGELOG.md` — permanent change history.
- `docs/VERSION` — current semantic version.

See [operations](docs/OPERATIONS.md) and [changelog](docs/CHANGELOG.md).

The legacy GitHub repository `lahosjesse/socialmedia-uploader` is only the Pages
deployment target. Its existing OAuth, Terms, Privacy and verification URLs
must remain stable.

## Security

This directory contains no API credentials, OAuth tokens, passwords, sessions,
cookies or user media.

## License

MIT

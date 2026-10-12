# Engine Bot documentation

This repository contains the Engine Bot documentation site, built with Mintlify.

## Structure

- `index.mdx` — Engine Bot overview
- `changelogs/` — versioned product updates
- `docs.json` — site configuration and navigation

## Development

Install the Mintlify CLI and run the local preview:

```bash
npm install -g mint
mint dev
```

The preview is available at `http://localhost:3000`.

Changes pushed to the default branch are published through the Mintlify GitHub integration.

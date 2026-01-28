# Aventor Docs

User documentation for Aventor, the AI‑powered ad creation platform.

- Docs site: https://docs.aventor.ai
- Product: https://aventor.ai

## About

This repo contains the Mintlify documentation site for Aventor. It covers getting started, the ad creation workflow, attachments, campaign launch, and platform integrations.

## Local preview

Install the Mintlify CLI:

```
npm i -g mint
```

Run the dev server from the repo root (where `docs.json` lives):

```
mint dev
```

Preview at `http://localhost:3000`.

## Structure

- `docs.json` — navigation and site settings
- `*.mdx` — documentation pages
- `images/` — screenshots and media
- `logo/` — brand assets used by the docs site

## Contributing

Keep changes user‑focused and accurate to the current product. Every page should include frontmatter (`title`, `description`) and use Mintlify components for scannable content.

## Support

If you spot an error or want a new page, reach out at `info@aventor.ai`.

# OIDC Project docs

This repository contains Mintlify documentation for an OpenID Connect project.

## Preview locally

Install the Mintlify CLI:

```bash
npm i -g mint
```

Run the preview server from this directory:

```bash
mint dev
```

Open `http://localhost:3000`.

## Validate links

```bash
mint broken-links
```

## Customize before publishing

- Replace `OIDC Project` with your product name in `docs.json`.
- Replace `https://auth.example.com` with your issuer.
- Replace dashboard, support, and GitHub links in `docs.json`.
- Update endpoint paths if your provider uses different routes.
- Customize `AGENTS.md` with your terminology and content boundaries.

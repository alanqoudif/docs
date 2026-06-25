# Mibyan / Atlas Swarm Core One Docs

This repository contains the external Mintlify documentation for Mibyan, internally referred to as Atlas Swarm Core One. The application source used as the documentation source of truth lives in `atlas-swarm-core-1`.

## Structure

- `docs.json`: Mintlify navigation and site settings.
- `index.mdx`, `quickstart.mdx`: product introduction and first-user flow.
- `platform/`: naming, architecture, and product model.
- `agents/`: Atlas and specialist agent docs.
- `features/`: artifacts, export, memory, and swarm behavior.
- `developers/`: API, tools, and data model notes.
- `operations/`: deployment and environment runbooks.
- `atlas-swarm-core-1/`: the product app used to derive the docs.

## Local preview

Install the Mintlify CLI:

```
npm i -g mint
```

Run the docs preview from this directory:

```
mint dev
```

View the local preview at `http://localhost:3000`.

## Product app

To run the app:

```
cd atlas-swarm-core-1
pnpm install
pnpm dev
```

## Documentation rule

Prefer the codebase over marketing copy when documenting behavior. Some product pages describe roadmap-level capabilities; the external docs should distinguish current implementation from roadmap.

Never commit secrets from `.env` files.

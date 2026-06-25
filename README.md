# Mibyan Docs

This repository contains the public user documentation for Mibyan.

## Structure

- `docs.json`: Mintlify navigation and site settings.
- `index.mdx`, `quickstart.mdx`: product introduction and first-user flow.
- `features/`: user guides for outputs, export, and context.
- `agents/`: Atlas and specialist agent guides.
- `api-reference/`: public API status and access notes.

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

## Documentation rule

Write for Mibyan users first. Do not expose source paths, database schema, deployment details, secrets, or internal implementation notes in public pages.

Never commit secrets from `.env` files.

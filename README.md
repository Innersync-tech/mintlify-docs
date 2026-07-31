# Innersync docs (Mintlify)

**Canonical live documentation** for Innersync → [docs.innersync.tech](https://docs.innersync.tech) (Mintlify).

This repo (`mintlify-docs`) is the **source of truth**. The former Starlight site (`Innersync-tech/docs`) is archived after cutover.

## Custom domain (human)

Add `docs.innersync.tech` in the **Mintlify dashboard** site settings and complete DNS verification before retiring Starlight Pages.

## Local preview

```bash
npm i -g mint
mint dev
```

## Sync

Alphapy product docs sync from `alphapy/docs/` via GitHub Actions into `synced/alphapy/` (see alphapy workflow `sync-docs-to-mintlify.yml`).

## Agent rule

Prefer editing this repo for published docs unless a task explicitly names Starlight archive or a product-repo `docs/` source file.

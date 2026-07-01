# Rustzen Site

> Migrated to [`rustzen/rustzen-hub`](https://github.com/rustzen/rustzen-hub) under `apps/site`.
> This repository is now a legacy source snapshot. Make new website changes in
> `rustzen-hub/apps/site`.

Rustzen Site is the static official website for the Rustzen macOS tool Zen Clear.

## Scope

- Single-product marketing site for Zen Clear
- Public macOS download entrypoint for Zen Clear
- Creem checkout return page for Pro subscriptions

## Tool

- **Zen Clear**: a lightweight macOS cleaner for developer environments. Pro is
  sold as a Creem annual subscription at $10/year.
- The public download button now points at the Rustzen console API's stable
  latest download resolver.

## Stack

- Astro
- Vercel

`pnpm build` exports static files into `dist/`.

## Development

```bash
pnpm install --frozen-lockfile
pnpm dev
```

## Content Sources

- `docs/current-site-content.md` is a historical snapshot of the previous
  multi-product site, kept for reference only.

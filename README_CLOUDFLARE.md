# WATCHO Stremio Add-on — Cloudflare Workers

This package is ready to deploy on Cloudflare Workers.

## Main files

- `cloudflare-worker.js`: Worker version of the add-on, with stream upstreams included in the code.
- `wrangler.jsonc`: Cloudflare Workers configuration.
- `watcho-logo.png`: transparent PNG logo used by `/logo.png`.
- `server.js`: optional local/Node version for testing.

## Deploy with Wrangler

```bash
npm install -g wrangler
wrangler login
wrangler deploy
```

After deployment, install the add-on in Stremio using:

```txt
https://YOUR-WORKER.YOUR-SUBDOMAIN.workers.dev/manifest.json
```

## Manifest description

```txt
WATCHO brings movies, series, and anime together in a simple, fast, and organized Stremio experience.
```

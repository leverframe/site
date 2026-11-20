# leverframe/site

The Leverframe org landing page — **leverframe.dev**.

Hand-rolled static HTML/CSS, no build step. Signal-box aesthetic (amber action,
steel structure, charcoal ground, JetBrains Mono, flat 1px lines — no gradients,
no glow, no shadows).

## Deploy

```bash
npx wrangler deploy   # Workers assets, apex + www custom domains
```

Requires a Cloudflare session (`wrangler login`) or `CLOUDFLARE_API_TOKEN`
with Workers Scripts:Edit on the account.

## Local preview

```bash
npx wrangler dev     # or any static file server pointed at public/
```

## License

MIT.

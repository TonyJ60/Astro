---
'@astrojs/cloudflare': patch
---

Fixes prerendered pages returning 404 in `astro dev` when using a custom Worker entrypoint with the `cf()` handler from `@astrojs/cloudflare/fetch` or `@astrojs/cloudflare/hono`

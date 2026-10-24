# John Schlaerth — Cloudflare deployment

Cloudflare builds this repository’s main branch and deploys the johnschlaerth-portfolio Worker.

The [canonical repository](https://github.com/johnschlaerth/johnschlaerth.com) contains the complete source and original recovery archive. This deployment copy contains every required web asset, including local video playback.

Build and verify with `npm ci` and `npm run build`. Cloudflare uses `npx --yes wrangler@4.152.0 deploy`. Only `dist/` is public.

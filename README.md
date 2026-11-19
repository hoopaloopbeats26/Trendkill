# trendkill.ca

Trendkill Productions label site. Static page served by the Cloudflare Worker `trendkill` (assets only, no Worker script).

- `site/` - everything that is deployed (index.html, img/, icons, robots.txt, sitemap.xml)
- `wrangler.jsonc` - Worker config (assets from `./site`)
- `index.html`, `Trendkill_Cloudflare_Deploy.zip`, `_headers` at the repo root - the September 2026 upload; not used by `wrangler.jsonc` (assets come from `./site`). Left in place until Ron decides.

Working copies, older versions, merch cut files and drafts stay in `AI HQ/Ron Agent Outputs/Web/Website Builds 2026-10-08/Trendkill/` on Atlas and are not in this repo.

Rules: changes go on a branch and a preview first. Nothing is merged to `main` or deployed to trendkill.ca without Ron's yes on that exact change. No keys, tokens or passwords in this repo.

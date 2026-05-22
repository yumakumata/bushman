# BUSHMAN site

Bushman official site static files for Cloudflare Pages.

## Edit points

- `index.html`: HOME news and SNS links
- `pages/2828896/nextstage/index.html`: next stage details
- `pages/2805035/discography/index.html`: profile and works
- `assets/styles.css`: shared design
- `assets/`: local images used by the site

## Deploy

From this directory:

```bash
npx wrangler pages deploy . --project-name=bushman --branch=main --commit-message="Update Bushman site"
```

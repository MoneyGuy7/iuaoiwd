# Yaktonian Equity
Static site, no build step.
- GitHub Pages: push to a repo, Settings > Pages > deploy from branch (root).
- Cloudflare Pages: connect repo, build command empty, output directory `/`.
- Admin: /admin.html (default password `yaktonian`). Tabs: Daily returns (add, CSV upload), Holdings, Updates, FAQ, Benchmark, Site details, Publish.
  To publish: Admin > Publish > Download data.js, replace assets/data.js, push.

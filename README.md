# leadcatch-web

Static landing pages for LeadCatch Solutions and KnockTrakr.

## Structure

```
leadcatch-web/
  leadcatch-landing/     → useleadcatch.com
    index.html
    assets/
      reese.png
  knocktrakr-landing/    → knocktrakr.com
    index.html
```

## Deploying on Railway

### knocktrakr.com
1. New Service → Deploy from GitHub repo → this repo
2. Set root directory: `knocktrakr-landing`
3. Add custom domain: `knocktrakr.com`

### useleadcatch.com
1. New Service → Deploy from GitHub repo → this repo
2. Set root directory: `leadcatch-landing`
3. Add custom domain: `useleadcatch.com`

Railway auto-detects static HTML and serves it. No build step needed.

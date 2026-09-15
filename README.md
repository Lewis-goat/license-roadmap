# License Roadmap

State-by-state trade & occupational license requirements — electrician, HVAC (incl. EPA 608),
plumbing, notary (TX/CA/FL), CNA. Zero-JS static pages, Article + FAQPage + Breadcrumb
JSON-LD, canonical URLs, sitemap.

- Live: **https://lewis-goat.github.io/license-roadmap/**
- Source + research: `adsense-site2/` in the local workspace

## Rebuild locally

```bash
python3 build.py   # markdown in content/ -> dist/
python3 audit.py   # SEO gate: exits 1 on any failure
```

AdSense wiring is in place behind placeholder IDs; flips live once the site moves to its own
root domain. Related project: [Expat Tax Desk](https://expattaxdesk.com).

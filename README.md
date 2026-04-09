# NaplesV2K — Guide Hosting

Static site for Vikki's PDF guide downloads. Deployed on Vercel at `naplesv2k.com`.

## Structure

```
guides/           → HTML download pages (naplesv2k.com/guides/move)
public/files/     → PDFs and OG images
vercel.json       → Clean URLs + download headers
```

## Adding a New Guide

1. Copy an existing guide HTML to `guides/{slug}.html`
2. Update title, description, OG tags, and PDF filename
3. Drop PDF into `public/files/`
4. Optional: add 1200×630 OG image as `public/files/og-{slug}.jpg`
5. Push — Vercel auto-deploys

## Manychat Integration

Set redirect URL to: `https://naplesv2k.com/guides/move`

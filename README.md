# 殿堂館 Majesty Professional Photo — Landing Page

Bilingual (zh-Hant primary / English secondary) landing page for Majesty Professional Photo, a portrait photography studio in Wan Chai, Hong Kong.

## Stack

- Single self-contained `index.html` — pure HTML/CSS + ~50 lines vanilla JS, no frameworks, no build step
- Local images only (`images/`), Google Fonts + keyless Google Maps embed via CDN
- JSON-LD `LocalBusiness` schema, Open Graph tags

## Sections

Hero → trust bar → 9 service cards → why-us → gallery → 6-step process → pricing → reviews → FAQ → contact + map. Mobile gets a hamburger menu and a sticky bottom call/WhatsApp bar. Every CTA deep-links to WhatsApp (+852 9433 4338) with a prefilled message.

## Preview

```bash
python -m http.server 8000   # then open http://localhost:8000
```

Or just open `index.html` directly.

## Deploy

Static hosting — upload `index.html` + `images/` as-is (GitHub Pages, Netlify, Vercel, or the studio's current host).

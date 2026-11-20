# Astro AI marketing site (`astroaii.in`)

Static HTML/CSS site for product page, Play Store QR, SEO blogs, and `app-ads.txt`.

## Folder

```
website/
  index.html          # Landing — brand, features, QR install
  css/styles.css
  images/             # App logo + Play Store screenshots
    app-icon.png
    logo.png
    hero-banner.jpg
    shot-*.jpg
  blogs/              # SEO guides (kundli, hastrekha, forehead)
  robots.txt
  sitemap.xml
  app-ads.txt         # For AdMob when domain is live
```

## Preview locally

```bash
cd website
python3 -m http.server 8080
```

Open http://localhost:8080

## Publish on astroaii.in

1. Point DNS for `astroaii.in` (and `www`) to your host (Firebase Hosting, Netlify, Cloudflare Pages, etc.).
2. Upload / deploy the contents of this `website/` folder to the **site root**.
3. Confirm:
   - https://astroaii.in/
   - https://astroaii.in/app-ads.txt
   - https://astroaii.in/sitemap.xml
4. Play Console → Store listing contact details → Website → `https://astroaii.in`
5. Google Search Console → add `astroaii.in` → submit `sitemap.xml`

## SEO next steps

- Add more blog posts monthly (Hindi/Marathi versions help local search).
- Register in [Google Search Console](https://search.google.com/search-console).
- Keep Play Store + website keywords aligned: kundli, hastrekha, palm reading, forehead reading.

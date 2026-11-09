# Pit Wall Basics — F1 2026 Rules Explained

## Publish (GitHub Pages, ~10 min)
1. Create a free GitHub account → New repository named **f1-2026-guide** → Public.
2. "uploading an existing file" → drag in everything in this folder (keep the `images` folder) → Commit.
3. Settings → Pages → Source: *Deploy from a branch* → Branch `main`, folder `/ (root)` → Save.
4. After 1–2 min the site is live at `https://YOUR-USERNAME.github.io/f1-2026-guide/`.
5. In `index.html`, `robots.txt` and `sitemap.xml`, replace every `YOUR-USERNAME` with your GitHub username (edit on GitHub with the pencil icon).

## Google Analytics 4
1. analytics.google.com → Admin → Create property → Web data stream with your URL.
2. Copy the Measurement ID (`G-…`) and replace both `G-XXXXXXXXXX` in `index.html`.
3. Open the site, then check Reports → Realtime to confirm you appear.
4. Click events show up as `click_cta_read_rules`, `click_share_whatsapp`, `click_share_x`, `click_outbound_f1_results`.

## Google Search Console
1. search.google.com/search-console → Add property → **URL prefix** → your URL.
2. Choose **HTML tag**, copy the `content` value, paste it into the commented `google-site-verification` line in `index.html` and uncomment it → Verify.
3. Sitemaps → submit `sitemap.xml`. URL Inspection → paste your URL → **Request indexing**.

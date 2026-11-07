# October 2026, one tile per event

Static site. Deploy to Cloudflare Pages:

    npx wrangler login
    npx wrangler pages deploy . --project-name october-2026

Run those from inside this folder. Your site will be at https://october-2026.pages.dev
(or whatever project name you choose). `_headers` sets long-term caching for the images.

To preview locally: `python3 -m http.server` in this folder, then open http://localhost:8000.

Event summaries: Wikipedia Current events portal, CC BY-SA 4.0. Images: Wikimedia Commons,
each under the license listed in the page's Image credits.

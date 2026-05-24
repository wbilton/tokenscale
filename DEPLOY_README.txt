TOKENSCALE — CLOUDFLARE DEPLOY FOLDER
======================================
Last updated: May 21 2026

These are the ONLY files that go to Cloudflare Pages.
Upload ALL of them every time you deploy.

  index.html     → tokenscale.dev/
  story.html     → tokenscale.dev/story
  404.html       → tokenscale.dev/404
  og-image.png   → tokenscale.dev/og-image.png
  llms.txt       → tokenscale.dev/llms.txt
  robots.txt     → tokenscale.dev/robots.txt
  sitemap.xml    → tokenscale.dev/sitemap.xml

HOW TO DEPLOY
-------------
1. Go to dash.cloudflare.com
2. Workers & Pages → tokenscale (the Pages project, not the domain)
3. Deployments tab → Upload assets (top right)
4. Drag ALL files from this folder into the uploader
5. Hit Deploy

AFTER ANY EDIT SESSION
-----------------------
Claude updates files in DEPLOYMENT/_deployed_[date]_build/files/
Copy updated files here before dragging to Cloudflare.

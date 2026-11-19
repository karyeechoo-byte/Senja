# Senja — Shop Link Page

A single-page, mobile-first web app for customers to quickly view Senja's menu,
opening hours, and contact details — and tap straight through to WhatsApp or Maps.

Built as one self-contained `index.html` (no backend, no build step, no frameworks).
All content is sample data; nothing is saved between visits.

## Run locally

Just open `index.html` in any browser — no server needed.

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `senja-site`), public or private.
2. Initialize and push this folder (if git isn't already set up here, install it
   from https://git-scm.com/download/win first):

   ```bash
   cd senja-site
   git init -b main
   git add .
   git commit -m "Initial commit: Senja shop link page"
   git remote add origin https://github.com/YOUR_USERNAME/senja-site.git
   git push -u origin main
   ```

3. In the repository, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose branch **main** and folder **/ (root)**, then click **Save**.
6. Wait a minute or two — your site will be live at:

   `https://YOUR_USERNAME.github.io/senja-site/`

## Updating the site

Edit `index.html`, then:

```bash
git add index.html
git commit -m "Update site"
git push
```

GitHub Pages redeploys automatically after each push.

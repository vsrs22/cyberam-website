# CybeRam website

Static one-page website for **CybeRam** — digital twins and 3D models for industrial machinery.

## Files
- `index.html` — the whole page (HTML + inline styles)
- `assets/images/` — photos and 3D model images
- `assets/logo.svg` — Twin Cube logo (also used as the browser-tab icon)

## Publish on GitHub Pages
1. Create a new repository on GitHub (e.g. `cyberam-website`), Public.
2. Click **Add file → Upload files**, drag in everything from this folder (keep the `assets` folder), and **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After about a minute the site is live at `https://<your-username>.github.io/cyberam-website/`.

## Custom domain (optional)
In **Settings → Pages → Custom domain**, enter your domain (e.g. `www.cyberam.in`) and add the DNS records GitHub shows you at your domain provider.

## Contact form
GitHub Pages has no server, so the "Request a pilot" form opens the visitor's email app with the details filled in and addressed to vsrs22@gmail.com. To receive submissions without email apps, connect the form to a service such as Formspree and set the form's `action` to its URL.

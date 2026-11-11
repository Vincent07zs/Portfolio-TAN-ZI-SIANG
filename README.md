# Tan Zi Siang — Portfolio

Plain HTML / CSS / vanilla JS. No build step, no dependencies. Works on GitHub Pages (all paths are relative).

```
index.html
css/style.css
js/script.js
assets/images/  hero-portrait.webp · hero-reveal.webp · profile.jpg
assets/icons/
```

## Deploy to GitHub Pages
1. Create a repository (e.g. `portfolio`, or `<username>.github.io` for a root URL) on github.com.
2. Upload **the contents** of this folder so `index.html` sits at the repository root (drag & drop in the web UI, or `git add . && git commit && git push`).
3. Go to **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. After a minute the site is live at `https://<username>.github.io/<repository>/`.

## Editing
- **Projects:** open `js/script.js` and add objects to the `PROJECTS` array (title, description, tools, image, url). Placeholders fill the remaining slots (minimum 4 cards). Put cover images in `assets/images/`.
- **WhatsApp:** hidden by default. In `js/script.js` set `CONFIG.whatsapp.enabled` to `true` to show a WhatsApp button. The number is only used in the link and never printed on the page.
- **Hero images:** `hero-portrait.webp` (default) and `hero-reveal.webp` (revealed by the brush) must stay the same pixel size and aspect ratio (1024×1536). `profile.jpg` is used in the About section.
- **Colours:** CSS variables at the top of `css/style.css`.

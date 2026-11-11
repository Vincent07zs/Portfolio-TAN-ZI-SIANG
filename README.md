# Portfolio-TAN-ZI-SIANG
Plain HTML / CSS / vanilla JS. No build step, no dependencies. Works on GitHub Pages (all paths are relative).
```
index.html
css/style.css
js/script.js
assets/images/  profile.jpg · profile-cutout.webp · profile-reveal.webp
assets/icons/
```
Deploy to GitHub Pages
Create a repository (e.g. `portfolio`, or `<username>.github.io` for a root URL) on github.com.
Upload the contents of this folder so `index.html` sits at the repository root (drag & drop in the web UI, or `git add . && git commit && git push`).
Go to Settings → Pages. Under Build and deployment choose Deploy from a branch, branch `main`, folder `/ (root)`, then Save.
After a minute the site is live at `https://<username>.github.io/<repository>/`.
Editing
Projects: open `js/script.js` and add objects to the `PROJECTS` array (title, description, tools, image, url). Placeholders fill the remaining slots (minimum 4 cards). Put cover images in `assets/images/`.
WhatsApp: hidden by default. In `js/script.js` set `CONFIG.whatsapp.enabled` to `true` to show a WhatsApp button. The number is only used in the link and never printed on the page.
Portrait: `profile-cutout.webp` is the hero image (background removed) and `profile-reveal.webp` is the same photo in a lime duotone, shown by the brush effect. If you replace the photo, keep both files the same size and aspect ratio (1254×1104), or update `aspect-ratio` in `.portrait` in `css/style.css`.
Colours: CSS variables at the top of `css/style.css`.

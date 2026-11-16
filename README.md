# Tan Zi Siang — Portfolio

Personal multi-page portfolio site for **Tan Zi Siang (Vincent)**.

## Structure

```
portfolio/
├── index.html          # Home
├── about.html
├── skills.html
├── projects.html
├── awards.html
├── contact.html
├── css/style.css
├── js/main.js
├── assets/portrait.jpg
└── README.md
```

## Deploy on GitHub Pages

1. Create a new repository (e.g. `vincent-portfolio` or `tan-zi-siang`).
2. Upload the contents of this folder to the root of the repository (or push via git).
3. Go to **Settings → Pages**.
4. Under **Source**, select the branch (usually `main`) and folder `/ (root)`.
5. Save. Your site will be available at `https://<username>.github.io/<repo-name>/`.

## Local preview

Open `index.html` in a browser, or run a simple local server:

```bash
# Python
python3 -m http.server 8080

# Node
npx serve .
```

Then visit `http://localhost:8080`.

## Customisation

- Replace `assets/portrait.jpg` with a new photo if needed.
- Update contact links and availability text in the HTML files.
- Add real project case studies inside `projects.html`.
- List awards inside `awards.html` when ready.

---

© 2026 Tan Zi Siang

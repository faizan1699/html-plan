## Educational HTML Multi‑Page Site

This project is a **pure HTML** multi‑page website designed for learning:

- **HTML structure and tags**
- **Git and GitHub**
- **GitHub Pages** static hosting

No CSS and no JavaScript are required.

### Pages

- `index.html` – Home page and overview, with many HTML examples.
- `projects.html` – Sample projects you can customize.
- `about.html` – About this educational site.
- `contact.html` – Example contact information.

Topic pages with focused examples:

- `html-text.html` – Headings, paragraphs, inline text tags.
- `html-lists.html` – Unordered/ordered lists and nested lists.
- `html-tables.html` – Tables with header, body, and basic attributes.
- `html-forms.html` – Forms, inputs, labels, textarea, button, select.
- `html-layout.html` – Layout tags like `div`, `section`, `article`, `aside`, `header`, `footer`.
- `html-media.html` – Images, audio, and video tags.

### How to open locally

1. Open this folder in your file manager.  
2. Double‑click `index.html` (or open it in your browser).  
3. Use the links on the page to move between topics.

### How to publish on GitHub Pages

1. Create a repository on GitHub (for example `html-education-site`).  
2. In this folder, run:

```bash
git init
git add .
git commit -m "Initial educational HTML site"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

3. On GitHub, go to **Settings → Pages**.  
4. Set **Source** to **Deploy from a branch**, select branch `main` and folder `/ (root)`.  
5. After a minute, GitHub will show a URL where your site is live.



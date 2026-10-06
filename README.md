# TonyYZ.github.io

Personal academic website of Yutong Zhou. Plain HTML and CSS — no framework, no build step.

## Files

- `index.html` — page content
- `style.css` — styles
- `CV.pdf` — add your CV here (linked from the CV section)

## Deploy with GitHub Pages

1. Create a public repository on GitHub named exactly `TonyYZ.github.io`.
2. Add `CV.pdf` to the repository root.
3. Push the files:

   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/TonyYZ/TonyYZ.github.io.git
   git push -u origin main
   ```

4. On GitHub, open **Settings → Pages** and make sure the source is **Deploy from a branch**, branch `main`, folder `/ (root)`.
5. After a minute or two, the site is live at <https://tonyyz.github.io/>.

## Local preview

Open `index.html` directly in a browser. No server is required.

## Editing

All content lives in `index.html`. Each research and project title has an `id`, so entries can be linked directly (for example `https://tonyyz.github.io/#embodied-lot`).

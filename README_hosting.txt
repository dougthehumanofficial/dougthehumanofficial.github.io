# Sage Space — Single-file Hosting Cheatsheet

## Fastest publish on GitHub Pages (user site)
1) Create a repo named **dougthehumanofficial.github.io** (exactly).
2) Upload **index.html** (this file) at the root and commit.
3) Visit https://dougthehumanofficial.github.io/ to load it.

## Or publish from any project repo
- Put the file in **/docs/index.html**.
- In GitHub -> Settings -> Pages: Source = `main` and Folder = `/docs`.
- Open the URL shown by Pages.

## Netlify drag‑and‑drop
- Go to app.netlify.com -> Sites -> **Add new site** -> **Deploy manually**.
- Drag **index.html**. Netlify will host it at a random subdomain.
- Optional: connect a custom domain and point DNS to Netlify.

## Common 404 fixes
- Ensure the filename is exactly **index.html** (case‑sensitive).
- Ensure you deployed from the branch/folder that Pages is reading.
- If using a user site (`username.github.io`), the repo name must match.
- If using a project site, enable Pages and place the file where it expects.
- Clear browser cache / wait for Pages to finish building.


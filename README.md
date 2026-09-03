# Resume site

Static single-page site for GitHub Pages.

## Files
- `index.html` – the whole site (HTML + CSS + a few lines of JS)
- `Emmett_Normand_Resume.pdf` – add your resume PDF here; the download button links to it
- `CNAME` – put your Porkbun domain on one line (e.g. `example.com`) once DNS is set

## Deploy
1. Create a public repo named `<username>.github.io` and push these files to `main`.
2. Settings > Pages > Source: Deploy from a branch, `main` / root.
3. Porkbun DNS: A records for root to 185.199.108.153 / .109.153 / .110.153 / .111.153; CNAME `www` to `<username>.github.io`.
4. Settings > Pages > Custom domain: your domain. Wait for the check, then enable Enforce HTTPS.

## Editing
Everything is in `index.html`. Search for "placeholder" and "add specifics" to find the spots that still need your content.

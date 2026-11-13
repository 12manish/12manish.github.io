# Manish Kumar Shukla portfolio — GitHub Pages edition

## Free publishing at https://12manish.github.io

1. Sign in to GitHub as **12manish**.
2. Create a **public** repository with the exact name **12manish.github.io** (unless it already exists).
3. Upload the **contents** of this folder (not the parent folder): `index.html`, `github-projects.html`, `.nojekyll`, and the `assets` directory. Use **Add file → Upload files → Commit changes**.
4. Go to **Settings → Pages → Build and deployment**. Select **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
5. Visit **https://12manish.github.io** once GitHub Pages finishes publishing.

Your projects page will be `https://12manish.github.io/github-projects.html`.

## All public GitHub repositories

`github-projects.html` uses the public GitHub API at `https://api.github.com/users/12manish/repos` to show up to 1,000 public repositories, with search, language filters, and sorting. It does not require an API token, build step, backend, or paid service. GitHub API rate limits apply; if the API fails, visitors are offered a direct GitHub repositories link. Private repositories cannot be shown without making them public. A GitHub code repository is not automatically a runnable interactive demo; add a deployed HTTPS demo URL to the repository Homepage field when available.

## Optional custom domain manishshukla.dev

`.dev` domain registration is **not included for free** with GitHub Pages. If you own this domain, verify it in GitHub, add the domain in repository **Settings → Pages → Custom domain**, then configure DNS with your registrar per GitHub documentation (https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site). Do not create a `CNAME` file with a domain you have not bought and configured. Enable **Enforce HTTPS** when available. `.dev` is HTTPS-only for browsers.

## Contact form and privacy

The contact form opens the user's email client and does not submit to a server. WhatsApp and email buttons are direct contact methods. Resume PDFs are public; inspect them before publishing. Work examples on the homepage are illustrative, while the GitHub gallery links to real public repositories.

## Local testing

Run `python -m http.server 8000` and open `http://localhost:8000`. You can also open `index.html` directly. The live GitHub gallery needs internet access.


## November 2026 portfolio update

- Updated hero with 1,500+ academic projects, 8 real-world projects, and 6 months of teaching (owner-supplied claims).
- Added detailed Core Skills section for Tableau, Power BI, R, Python, machine learning, deep learning, image processing and n8n.
- Added Smart India Hackathon 2025 Team TigerBytes / Aqua Genesis case-study section based on the supplied presentation (PS 25067). Runner-up status and location are owner-reported and not independently substantiated by that slide deck.
- Preserved existing GitHub project gallery, resume downloads and static email/WhatsApp contact workflow.

### Updating the deployed site
Upload the replacement `index.html` to the repository root via Add file > Upload files (or edit via GitHub). Keep the `assets` folder and `github-projects.html` unchanged. Commit to `main`; GitHub Pages redeploys automatically. To update all contents, upload the extracted folder contents, not the ZIP.

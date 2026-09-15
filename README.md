# Baigang Chen — personal website

A simple academic homepage with research, publications, a CV, and a Fun facts photo gallery. Plain HTML and CSS, with no build step or dependencies.

GitHub Pages address after publishing: **https://baigang0000.github.io/website_baigang/**

## Enable publishing

Open [Settings → Pages](https://github.com/Baigang0000/website_baigang/settings/pages). Under Build and deployment, choose **Deploy from a branch**, **main**, and **/(root)**, then click **Save**. Keep the repository public for GitHub Pages on the free plan. Publishing may take up to 10 minutes.

The `.nojekyll` file publishes these static files directly. After setup, changes committed to `main` are automatically published.

## Edit your site on GitHub

| What to change | File |
| --- | --- |
| Biography, research, publications, name | [index.html](index.html) |
| Fun facts and photo gallery | [fun-facts.html](fun-facts.html) |
| Colors, fonts, spacing | [styles.css](styles.css) |
| CV download | [Baigang_Chen_CV.pdf](Baigang_Chen_CV.pdf) |
| Profile photo | [portrait.jpg](portrait.jpg) |
| Gallery photos | [photos/](photos/) |

Open a text file, click the pencil icon, edit it, and commit the changes. The name, contact details, and research-interest sidebar appear in both HTML pages; update both when those details change.

To replace the CV, upload the new PDF with the same filename, then change the `?v=...` value in the CV link on both pages to a fresh value, such as the update date. The current PDF is the unmodified `CBG_cv (6).pdf` supplied on September 15, 2026.

To add photos, upload them into `photos/` and add the corresponding image and full-size link in `fun-facts.html`.

## Name and address

The visible name and browser title can be edited in the HTML files. This repository’s name controls the `/website_baigang/` part of its Pages address. A repository named `Baigang0000.github.io` would use the account’s root Pages address instead.

A custom domain such as `baigangchen.com` requires separate registration and renewal. If the public address changes, update the `og:url` metadata in both HTML pages. All local asset and navigation links are relative, so they work under a project path or a custom domain.

## Local preview

Run `python -m http.server 8000` in this folder and open http://localhost:8000/ .

## GitHub documentation

- [GitHub Pages and free hosting](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)
- [Publishing from a branch](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

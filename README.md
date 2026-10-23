# Boris Prokhorov

Concise academic webpage with a short research bio, publications, and teaching, inspired by https://mstou.github.io/. The contact address is shown as plain text `firstname.lastname@epfl.ch`, with no direct email link. There is no CV download. The portrait has a straightened horizon and is embedded in the page. The design uses a light sky-blue background and mint accents.

## Preview and edit

Open `index.html` in your browser. All styling and the favicon are included in that file. There are no external fonts, scripts, dependencies, or build steps.

Edit the text directly in `index.html`. The portrait is stored as an optimized JPEG data URL in the image element; no separate photo file needs to be pushed. The original photo is unchanged in Downloads.

## Publish

The existing Git remote is `https://github.com/barbarislav/barbarislav.github.io.git`, and the branch is `main`.

1. Commit and push `index.html` to the root of this repository on `main`. Include the empty `.nojekyll` file to skip Jekyll processing. `README.md` is optional for hosting.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**, **main**, and **/(root)**, then save.
4. The site will be available at **https://barbarislav.github.io/**. Check the Pages deployment status; updates can take up to 10 minutes.

For example, run these commands from this directory after reviewing the page:

```sh
git add index.html .nojekyll README.md
git commit -m "Add personal academic homepage"
git push origin main
```

The repository must be public when using GitHub Free. No custom GitHub Actions workflow or `_config.yml` is required. The older `README copy.md` is a generic template guide and does not need to be uploaded.

## Address options

- Keep the current account and repository: **https://barbarislav.github.io/**.
- A project repository named `bpro` under the current account would normally use **https://barbarislav.github.io/bpro/**.
- **https://bpro.github.io/** requires control of a GitHub user or organization named `bpro`, with a repository named `bpro.github.io`. It cannot be assigned just by editing HTML, renaming this repository, or adding a `CNAME` file.
- Keep the current account and connect a custom domain you own through **Settings → Pages → Custom domain** and your domain's DNS settings. You do not need a custom domain to publish the current site.

If the final address changes, update the `canonical` link and `og:url` in `index.html` as well. Neither changes the hosting address by itself.

## References

- [GitHub Pages quickstart](https://docs.github.com/en/pages/quickstart)
- [Configure a publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [About GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages)
- [Manage a custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)

Publication links are from the supplied CV. The SODA 2027 and NeurIPS 2026 “to appear” statuses are also listed on [Michael Kapralov's homepage](https://theory.epfl.ch/kapralov/). Venue years and author order for the published papers follow the CV. “Attention under Bounded Key–Query Similarity: Space Complexity and Transformer Anisotropy” is listed as a preprint with authors in the order shown in the supplied PDF. It intentionally has no link; add an arXiv link to its entry after posting. The PDF is not included in the repository. Superscript (α–β) markers at the start of the first three author lists indicate alphabetical author order.

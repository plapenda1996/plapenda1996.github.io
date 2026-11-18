# Do Young Kim — personal academic website

Source for https://plapenda1996.github.io, built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme (v1.x) and deployed by GitHub Actions to GitHub Pages.

## Where to edit

| What                        | File                                    |
| --------------------------- | --------------------------------------- |
| Name, site URL, site-wide settings | `_config.yml`                    |
| Home page bio and profile photo    | `_pages/about.md` (photo: `assets/img/prof_pic.jpg`) |
| Publications                | `_bibliography/papers.bib` (`selected = {true}` puts a paper on the home page) |
| News items                  | `_news/*.md`                            |
| Projects                    | `_projects/*.md`                        |
| CV page                     | `_data/cv.yml`                          |
| Email and social links      | `_data/socials.yml`                     |

Every push to `main` rebuilds the site with `.github/workflows/deploy.yml`, which publishes the built site to the `gh-pages` branch. GitHub Pages must be set to deploy from the `gh-pages` branch (Settings → Pages).

## Custom domain

To serve the site at a custom domain (for example `doyoungkimoptics.com`):

1. Point the domain's DNS at GitHub Pages (A records for the apex domain and a `CNAME` record for `www` pointing to `plapenda1996.github.io`).
2. Enter the domain under Settings → Pages → Custom domain and enable "Enforce HTTPS".
3. Set `url:` in `_config.yml` to the custom domain and add a `CNAME` file containing the domain to the repository root.

Template documentation lives in `docs/` (see `docs/CUSTOMIZE.md`).

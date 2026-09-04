# Haoyue Sun — Academic Homepage

A bilingual (English/Japanese), GitHub Pages–ready academic homepage built with Jekyll. The public site is intentionally limited to a profile, CV, current research overview, and contact information. It uses no paid service, database, or external JavaScript library.

## Preview locally

If Ruby and Bundler are available:

```bash
bundle install
bundle exec jekyll serve
```

You can also push the project to GitHub and use GitHub Pages as described below.

## Publish with GitHub Pages

1. Create a public repository. For the cleanest URL, name it `YOUR-USERNAME.github.io`.
2. Upload every file and folder in this project to the repository root.
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Your site will be available at `https://YOUR-USERNAME.github.io/` after GitHub finishes building it.

If you use a normal repository name such as `academic-homepage`, set this in `_config.yml` before publishing:

```yml
url: "https://YOUR-USERNAME.github.io"
baseurl: "/academic-homepage"
```

## Replace the placeholders

- Portrait: replace `assets/images/profile-placeholder.svg` with `assets/images/profile.jpg`, then change the image path in `index.md` and `ja/index.md`.
- Email: search the project for `your.email@example.com` and replace every occurrence.
- CV PDF: add `assets/files/haoyue-sun-cv.pdf`; replace the disabled PDF label on both CV pages with a link.
- Content: edit the English Markdown files in the root and the matching Japanese files under `ja/`.

## Site structure

```text
index.md                    English profile
cv.md                       English CV
current-research.md         English research overview
contact.md                  English contact page
ja/                         Matching Japanese pages
_layouts/default.html       Shared page layout
_includes/                  Shared header and footer
_data/navigation.yml        English and Japanese navigation
assets/css/style.css        All visual styling
assets/js/main.js           Mobile menu and current year
assets/images/              Portrait and favicon
```

## Content recommendation

Keep the undergraduate fieldwork section if it demonstrates research design, interviewing, data collection, or analysis. Include only one or two student activities with a clear connection to coordination, communication, leadership, or public engagement. Avoid turning the profile page into a complete activity list; the CV can hold the full record.

Do not place unpublished manuscripts, detailed research proposals, private data, or confidential results in the public repository. Share those materials directly with prospective supervisors when appropriate.

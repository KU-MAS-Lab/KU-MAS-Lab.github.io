# MAS Lab GitHub Pages Starter

A Jekyll + GitHub Actions starter for the **Multimodal Acoustic Systems Laboratory (MAS Lab)** at Korea University.

## 1. Replace the placeholders

- `_config.yml`
  - `url`
  - `email`
  - `address`
- `_members/seongwook-choi.md`
  - email, biography, photo
- `join.md`
  - contact email

## 2. Add visual assets

Put these files in `assets/img/`:

- `mai-logo.png` — transparent MAS Lab logo/wordmark
- `hero.jpg` — optional research/lab hero image
- member photos as needed

`branding-reference.png` is the uploaded MAI branding collage and is included only as a reference; it is not used by the website.

## 3. Local preview

Install Ruby 3.2+, then:

```bash
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000`.

## 4. GitHub Pages deployment

1. Create a GitHub organization or use your personal account.
2. For an organization site, create a repository named `<ORG>.github.io`.
3. Push these files to the `main` branch.
4. Go to **Settings → Pages → Build and deployment → Source → GitHub Actions**.
5. The included workflow builds and deploys the site whenever `main` changes.

## 5. Routine updates

- New member: add a Markdown file under `_members/`.
- New news item: add a Markdown file under `_news/`.
- New paper: add a BibTeX entry to `_bibliography/publications.bib`.
- Change colors/layout: edit `assets/css/main.css`.

## Design notes

The layout is inspired by modern academic-lab GitHub Pages sites: sticky navigation, a large hero, concise research cards, Markdown-driven member/news collections, and BibTeX-driven publications. It is an original implementation and does not copy another site's source files.

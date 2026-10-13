# Pranav Shriram Arunachalaramanan — Personal Website

A minimal Jekyll site (same structure as `../website-new`). No theme gem — everything is in this folder.

## Run locally

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Customize

| What | Where |
|---|---|
| Name, email, links, nav | `_config.yml` |
| Bio / home page | `index.md` |
| Profile photo | put it in `files/` and set `author.photo` in `_config.yml` |
| Publications (Research page) | `_data/publications.yml` |
| CV | add `files/CV.pdf` and a nav entry in `_config.yml` |
| Styling | `assets/css/style.css` |

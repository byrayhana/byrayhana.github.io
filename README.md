# byrayhana.github.io

Source for my personal portfolio site → **https://byrayhana.github.io**

A single-page portfolio built as a lightweight [Jekyll](https://jekyllrb.com/) site (custom layout, no external theme gem) and hosted on **GitHub Pages**. Sections: About · Skills · Selected Work · Publications · Experience.

## Local preview

```bash
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```

## Structure

```
_config.yml            site settings & profile links
_layouts/default.html  page shell (nav, head, footer)
index.html             all page content (front-matter driven)
assets/css/style.css   dark, responsive theme
```

Edit links/text in `_config.yml` and `index.html`.

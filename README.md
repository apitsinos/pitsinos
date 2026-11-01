# Alex Pitsinos

Personal website built with Jekyll and [Hitchens](https://github.com/patdryburgh/hitchens) by Pat Dryburgh.

## Deployment

In Settings → Pages, choose **Deploy from a branch**, **main**, and **/(root)**.
Site URL: https://apitsinos.github.io/pitsinos/

## Editing

Edit `index.html` for the homepage, `about.html` for the biography, and `_config.yml` for site settings. `404.html` handles missing pages.

The theme is loaded through `jekyll-remote-theme`; its original styling, fonts, licenses, and attribution are preserved. The local `theme-source/` directory is an upstream reference copy, excluded from the build and upload.

## Local preview

With a current Ruby and Bundler:

```
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000/pitsinos/.

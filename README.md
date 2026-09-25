# Jacob Kingi — academic profile

Personal website built with [Academic Pages](https://github.com/academicpages/academicpages.github.io).

Public address: https://ghostgeek6113.github.io/jacobkingi.github.io/

## Editing

- `_pages/about.md`: biography and selected publication
- `_pages/research.md`: research interests
- `_pages/publications.html`: publication list
- `_pages/contact.md`: public email addresses and profile links
- `_config.yml`: identity, sidebar, and site URL
- `_data/navigation.yml`: navigation
- `assets/css/profile.css`: custom styling

Sample template content is excluded from the published website in `_config.yml`.

## Publishing

In repository Settings → Pages, select **Deploy from a branch**, **master**, and **/(root)**. GitHub Pages builds the Jekyll site when changes are committed.

The repository is a project site under the `ghostgeek6113` account. Keep `url` set to `https://ghostgeek6113.github.io` and `baseurl` set to `/jacobkingi.github.io` unless the repository or domain changes.

## Local preview

With Ruby 3.1–3.4 and Bundler installed:

```sh
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve
```

Visit http://127.0.0.1:4000/jacobkingi.github.io/.

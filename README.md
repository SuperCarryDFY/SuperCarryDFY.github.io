# Fengyuan Dai — personal academic website

Personal website at <https://supercarrydfy.github.io>, built with Jekyll and the existing [Academic Pages](https://github.com/academicpages/academicpages.github.io) template.

## Update content

- `_pages/about.md`: introduction and research interests.
- `_data/publications.yml`: selected publications, author lists, summaries, and paper/server links. The homepage, publications page, and CV all use this data; retain the explicit acceptance status when applicable.
- `_includes/education.html` and `_includes/awards.html`: shared education and awards.
- `_pages/cv.md`: web CV and technical skills.
- `files/cv.pdf`: downloadable CV, copied from the updated resume.
- `_config.yml`: author profile, social links, and site metadata.
- `_data/navigation.yml`: top navigation.
- `_sass/_profile.scss`: small presentation adjustments for publications.

Template demo pages, posts, and collections remain in the repository for reference but are excluded from the published site in `_config.yml`.

## Local preview

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

Visit <http://localhost:4000>. To check a production build:

```sh
bundle exec jekyll build
```

GitHub Pages uses `_config.yml`. Commit and push the content updates to the repository's publishing branch to deploy through its existing Pages configuration.

## Credits

Academic Pages is based on [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/). See `LICENSE` for the template license.

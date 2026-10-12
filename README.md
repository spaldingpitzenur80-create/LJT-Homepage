# LJT-Homepage

Personal academic homepage of Junteng Liu, built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template (a fork of [Minimal Mistakes](https://mademistakes.com/work/minimal-mistakes-jekyll-theme/)).

## Site pages

- **About** (`_pages/about.md`, served at the site root): personal introduction, research interests, academic background, research experience, skills, publications, and contact information.
- **Publications** (`_pages/publications.html`): the publication list generated from the Markdown files in `_publications/`.

Personal details are configured in `_config.yml` and `_data/authors.yml`; header links are configured in `_data/navigation.yml`.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

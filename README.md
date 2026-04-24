# Slavik Balabolka CV

This repository contains the source for Slavik Balabolka's CV site built with Jekyll.

## Updating the CV

Most content lives in [`_data/data.yml`](./_data/data.yml). Edit that file to update experience, skills, links, and other profile details.

The site configuration is in [`_config.yml`](./_config.yml), including the title, custom domain, and Jekyll settings.

The published site is available at <http://bolkabolka.github.io>, and the printable version is at <http://bolkabolka.github.io/print>.

## Preview locally with Docker

```sh
docker-compose up
```

This starts the site at <http://localhost:4000>. Changes to `_data/data.yml` and templates will be picked up automatically after a short rebuild.

## Preview locally with Ruby

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

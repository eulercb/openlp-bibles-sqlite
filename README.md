# openlp-bibles-sqlite

Web Scraping from bible.com to generate sqlite files to OpenLP software.

## Development

[![Actions Status](https://github.com/estevao90/openlp-bibles-sqlite/workflows/LintingAndTests/badge.svg)](https://github.com/estevao90/openlp-bibles-sqlite/actions)

## Dependencies

```shell
# install pipenv globally
sudo pip install pipenv -U

# create project virtualenv
pipenv install --dev

# active virtualenv
pipenv shell
```

## Helpful developer commands

```shell
# lint
pylint --load-plugins pylint_quotes src/*
```

# Sinara Contribution Guidelines

Documentation for contributing to Sinara projects, built with [Zensical](https://zensical.org/docs/get-started/).

## Local preview

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
zensical serve
```

Open http://127.0.0.1:8000 to preview the site.

## Build

```bash
zensical build
```

Static output is written to `site/`.

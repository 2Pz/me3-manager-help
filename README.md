# ME3 Manager Help

ME3 Manager documentation and blog.

## Quick Start (uv)
```sh
# Serve with live reload
uv run mkdocs serve

# Build the site
uv run mkdocs build
```

## Alternative (pip)
```sh
python -m venv .venv
source .venv/bin/activate
pip install mkdocs mkdocs-material pymdown-extensions
mkdocs serve
```

## Structure
- `docs/` content
- `mkdocs.yml` config
- `docs/blog/` posts
- `docs/assets/` images

# greet-ci

A small greeting program with a GitHub Actions CI workflow.

## Install

```
uv lock
```

## Run

```
uv run --locked python greet.py Hee   # Hello, Hee!
uv run --locked python greet.py       # Hello, world!
```

## Check

```
uv run --locked pytest -q greet.py
uv run --locked black --check greet.py
uv run --locked flake8 greet.py
uv run --locked mypy greet.py
uv build
```

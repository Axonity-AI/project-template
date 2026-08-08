# {{PROJECT_NAME}}

## Overview
One paragraph: what this project does and why it exists.

## Quickstart (dev)
```bash
./scripts/setup.sh    # one-time: installs deps + activates pre-commit hooks
./scripts/run_local.sh
```
`run_local.sh` creates a virtualenv, installs dependencies, loads `.env`/`.env.example`, and starts the app.

## Run tests
```bash
pytest -q
```

## Deploy notes
```bash
docker build -t {{PACKAGE_NAME}} -f docker/Dockerfile .
docker compose -f docker/compose.yml up
```

## Contacts
Owner: TBD

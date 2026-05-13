# Investment AI Dashboard

This repository contains an automatically generated investment dashboard.

## Main files

- `docs/index.html`: the website published by GitHub Pages.
- `docs/data/`: latest CSV data used by the dashboard.
- `investment_ai.py`: Python script that updates the analysis.
- `requirements.txt`: Python dependencies.
- `.github/workflows/scheduled_update.yml`: automatic scheduled update workflow.

## GitHub Pages setup

Go to:

Settings → Pages

Then select:

- Source: Deploy from a branch
- Branch: main
- Folder: /docs

Your dashboard URL will look like:

https://YOUR_USERNAME.github.io/YOUR_REPOSITORY_NAME/

## Automatic updates

Go to:

Actions → Scheduled Investment AI Update → Run workflow

The workflow is also scheduled Monday to Friday at 21:30 UTC.

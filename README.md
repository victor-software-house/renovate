# renovate

This repository runs [Renovate](https://docs.renovatebot.com/) every week over the organization's active public repositories.
Renovate opens draft pull requests and keeps them up to date.
It never merges them and never turns on auto-merge.

The run is a reusable workflow in [victor-software-house/actions](https://github.com/victor-software-house/actions), described in its `docs/renovate.md`.
`.github/workflows/renovate.yml` calls it, pinned by commit.

## Runs

The workflow runs on Mondays at 09:00 UTC.
A manual run is a dry run unless its `dry-run` input is off.

## Scope

A public repository is in scope when its default branch has at least 2 real commits in the last 30 days.
The reusable workflow's documentation defines a real commit.

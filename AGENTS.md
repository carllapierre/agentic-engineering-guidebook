# AGENTS.md

## Project Purpose

This repository is a markdown-first guidebook for agentic engineering.
Primary deliverable: clean Markdown content under `docs/`, published as a simple static site via MkDocs.

## Tech Stack

- Documentation: Markdown (`.md`)
- Site generator: MkDocs + Material for MkDocs
- CI/CD: GitHub Actions (build + deploy)

## Repository Conventions

- Keep all authored content inside `docs/`.
- Keep helper automation in `scripts/`.

## Quality Gate

Before finishing substantive doc changes:

1. Run `mkdocs build --strict`
2. Fix broken links/nav warnings
3. Confirm `docs/index.md` TOC and `mkdocs.yml` nav are current

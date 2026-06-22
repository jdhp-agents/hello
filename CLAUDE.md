# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project bootstrap

This project is generated from the template [`jdhp-agents/webapp-template`](https://github.com/jdhp-agents/webapp-template) via [Copier](https://copier.readthedocs.io/). The only file checked in before scaffolding is `metadata.yml`, which holds the Jinja substitution variables (e.g. `project_name`).

To scaffold (or re-scaffold) the project:

```sh
copier copy --data-file metadata.yml https://github.com/jdhp-agents/webapp-template.git .
```

Use `/copier-init` (the built-in skill) to let Claude run this step automatically.

## After scaffolding

Once the template has been applied, update this file with:
- Build, lint, and test commands specific to the generated stack.
- High-level architecture of the generated code.

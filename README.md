# Zeal Docs (Mintlify)

> Zeal's Mintlify documentation project: MDX guides, API reference and AI-tool docs rendered by Mintlify, configured through `docs.json`.

Currently based on the Mintlify starter kit (theme "mint", `name` still "Mint Starter Kit" - branding not yet customized).

## Structure

```text
docs.json        Mintlify site config (theme, colors, navigation tabs/groups)
index.mdx        landing page
quickstart.mdx   getting started
development.mdx  development guide
essentials/      core guide pages
api-reference/   API reference pages
ai-tools/        AI tooling docs
images/, logo/   assets
CONTRIBUTING.md  how to contribute
AGENTS.md        notes for AI assistants working on this repo
.mintignore      build exclusions
```

## Workflow

Edit or add `.mdx` pages, register them in `docs.json` navigation, preview locally with the Mintlify CLI (`mint dev`), and open a PR. Mintlify deploys on merge (git-connected).

## To-dos visible from the config

- Customize `name`/branding away from the starter kit
- Fill `api-reference/` with the real Zeal API pages

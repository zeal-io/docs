<h1 align="center">Zeal Docs (Mintlify)</h1>

<p align="center"><i>Zeal's Mintlify documentation project: MDX guides, API reference and AI-tool docs rendered by Mintlify, configured through `docs.json`.</i></p>

<p align="center">![Language](https://img.shields.io/badge/lang-MDX-F97316) ![Stack](https://img.shields.io/badge/stack-Mintlify-339933) ![Status](https://img.shields.io/badge/status-active-2EA44F) ![Visibility](https://img.shields.io/badge/repo-public-24292F) ![License](https://img.shields.io/badge/license-MIT-blue)</p>

---
## Contents

- [Structure](#structure)
- [Workflow](#workflow)
- [To-dos visible from the config](#to-dos-visible-from-the-config)

Currently based on the Mintlify starter kit (theme "mint", `name` still "Mint Starter Kit" - branding not yet customized).

<p align="right"><a href="#contents">Back to contents</a></p>

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

<p align="right"><a href="#contents">Back to contents</a></p>

## Workflow

Edit or add `.mdx` pages, register them in `docs.json` navigation, preview locally with the Mintlify CLI (`mint dev`), and open a PR. Mintlify deploys on merge (git-connected).

<p align="right"><a href="#contents">Back to contents</a></p>

## To-dos visible from the config

- Customize `name`/branding away from the starter kit
- Fill `api-reference/` with the real Zeal API pages

## License and contribution

Internal Zeal repository. License: MIT (see the LICENSE file).

Contribution: open a pull request against the default branch; keep changes minimal and described. For releases/deployments follow the platform CD process - never force-push shared branches.

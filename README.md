# GEO and Technical SEO Skill

This repository contains a Claude Code skill, five GEO/SEO agent instruction files, Python tools, JSON-LD schema examples, and sample audit/proposal files. It does not contain a packaged `geo` command-line application.

The [license](./LICENSE) credits Zubair Trabzada. Preserve that attribution and the MIT license when reusing these files.

## At a glance

| Field | Details |
|---|---|
| Skill entry point | [geo/SKILL.md](./geo/SKILL.md) |
| Supporting skills | [skills/](./skills/) |
| Agent instructions | [agents/](./agents/) |
| Python dependencies | [requirements.txt](./requirements.txt) |
| JSON-LD examples | [schema/](./schema/) |
| Sample files | [examples/](./examples/) |
| License | MIT; see [LICENSE](./LICENSE) |

## How to use

The `/geo ...` commands in [geo/SKILL.md](./geo/SKILL.md) are instructions for a compatible Claude Code skill host. They are not standalone shell commands installed by this repository.

For Python tools, install the declared dependencies in an isolated environment:

```sh
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

The PDF generator accepts a JSON audit-data file and optional output path:

```sh
python scripts/generate_pdf_report.py <audit-data.json> [report.pdf]
```

See each script's usage text before running it. The Flask prospect dashboard reads and writes under `~/.geo-prospects/`; inspect the data path before using it.

## What the tools measure

- The citability scorer applies text-structure heuristics and returns a score. It does not measure whether ChatGPT, Gemini, or another engine will cite a page.
- Brand scanning includes search prompts and manual-check guidance. It does not provide verified API-based citation tracking.
- The `llms.txt` tool checks or generates files using HTTP requests to the supplied site.
- The PDF script formats provided JSON data. It does not independently verify the audit findings.

Treat scores and recommendations as review aids. Check source pages, evidence, and current search-provider behavior before making business claims.

## Installation script boundary

`install.sh` and `install-win.sh` currently clone `zubair-trabzada/geo-seo-claude` and install its `geo` skill and agent files under the user's Claude directory. They do not install this `hmzainjamil` checkout. Review the scripts before running them or using them for updates.

For a local copy of this checkout, review the skill and agent files, then copy only the selected directories into the host's configured skill/agent locations. Confirm the destination and existing files before replacing anything.

## Repository map

| Path | Purpose |
|---|---|
| `geo/SKILL.md` | Claude Code skill workflow and command guidance |
| `skills/*/SKILL.md` | Focused GEO tasks |
| `agents/` | Specialist agent instructions |
| `scripts/` | Scoring, site fetching, schema/llms.txt support, PDF, CRM, and Flask tools |
| `schema/` | JSON-LD schema examples |
| `examples/` | Sample audit and proposal data |
| `tests/` | Fetch-page test |

## Data and side effects

Site-audit scripts make HTTP requests to URLs supplied by the user. The scripts may fetch public pages and save generated reports or files. The CRM dashboard reads and writes local prospect, audit, and proposal data under `~/.geo-prospects/`. Review inputs and outputs before sharing them.

This README update did not install dependencies, fetch a site, run the web app, or run tests.

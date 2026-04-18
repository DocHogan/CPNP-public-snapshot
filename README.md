# CPNP Public Snapshot

Static snapshot of the Supplement Plan project, deployed via GitHub Pages.

**Live site:** https://DocHogan.github.io/CPNP-public-snapshot/

## What this is

A frozen HTML snapshot of a structured daily nutritional supplement regimen,
intended for review by a restricted set of people. Not a public publication,
not under active development in this repo — the canonical source is an
Obsidian vault elsewhere. This repo is the *output artifact*.

## Updating

Generated from source by a Quartz v4 build pipeline at
`~/devspace/supplement-plan-site/`. To regenerate:

1. Edit source documents in the Obsidian vault.
2. `cd ~/devspace/supplement-plan-site && ./build.sh`
3. `./deploy.sh` (in the same dir) — copies `public/` here, commits, pushes.

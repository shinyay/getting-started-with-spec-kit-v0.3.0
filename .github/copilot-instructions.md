# Copilot Instructions for Spec Kit Workshop

## Repository Overview

This is a hands-on workshop repository for GitHub Spec Kit v0.3.0, teaching Spec-Driven Development (SDD) through 18 real-world scenarios across 4 difficulty levels.

## GitHub Pages (workshop-pages-theme)

This repository uses `shinyay/workshop-pages-theme` as a Jekyll remote theme for GitHub Pages.

### Theme Layouts
- `layout: home` — Landing page (`index.md`)
- `layout: step` — Individual scenario pages (18 scenarios, `step_number: 1-18`)
- `layout: cheatsheet` — Answer key pages linked to scenarios (`parent_step: N`)
- `layout: default` — Supplementary pages (WORKSHOP.md, SCENARIOS.md)

### Front Matter Requirements
Every page needs YAML front matter with at minimum: `layout`, `title`, and `permalink`.
Step pages also need `step_number`. Cheatsheet pages need `parent_step`.

### File Structure
- `index.md` — Home page (layout: home)
- `setup.md` — Step 0: Prerequisites
- `scenarios/*.md` — Steps 1-18 (layout: step)
- `scenarios/_answers/*.md` — Answer keys (layout: cheatsheet)
- `WORKSHOP.md` — Facilitator guide (layout: default)
- `SCENARIOS.md` — Scenario directory (layout: default)

### Important
- The `_config.yml` includes `scenarios/_answers` explicitly (Jekyll skips `_` dirs by default)
- Do not modify YAML front matter without understanding the theme layout system

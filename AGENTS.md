# AGENTS.md

## Repository overview

This repository is a personal academic website built with Hugo and the Wowchemy Academic theme. The site is primarily content-driven: Markdown files under content/ define the homepage, publications, posts, projects, talks, and other sections.

## Tech stack

- Hugo static site generator
- Wowchemy Academic theme
- Netlify deployment
- Go modules for theme dependencies

## Key paths

- content/ — main site content and sections
  - content/home/ — homepage sections
  - content/publication/ — publications with per-item folders
  - content/post/ — blog posts
  - content/project/ — projects
  - content/event/ — talks and events
- config/_default/ — Hugo and site configuration
- assets/ and static/ — custom assets, images, and static files
- exampleSite/ — reference example site from the theme
- netlify.toml — Netlify build/deploy settings
- view.sh — local preview command
- update_wowchemy.sh — helper for updating theme modules

## Working conventions

- Prefer small, targeted edits over broad rewrites.
- Preserve existing front matter in Markdown content files.
- Keep YAML formatting valid and consistent with the surrounding files.
- Reuse the existing content structure rather than introducing new patterns unless necessary.
- Avoid editing generated or vendored output unless explicitly requested.

## Common tasks

### Preview locally
Run:

```bash
./view.sh
```

This starts a local Hugo server for previewing changes.

### Build the site
Run:

```bash
hugo --gc --minify
```

### Update theme dependencies
Run:

```bash
bash ./update_wowchemy.sh
```

## Content guidance

- Homepage content lives in content/home/ and is typically organized as separate Markdown files.
- Publications should remain structured with a folder per publication, usually containing index.md and cite.bib.
- New sections should follow the existing Hugo/Wowchemy conventions and naming patterns.
- Images and media should generally live under assets/ or static/ and be referenced consistently.

## Deployment notes

The site is configured for Netlify via netlify.toml. Changes that look correct locally should also be safe to deploy through the standard Netlify pipeline.

## When making changes

- Check nearby files for the same section before introducing new structure.
- Keep content user-facing and polished.
- Preserve links, metadata, and section ordering where possible.
- If changing theme behavior or configuration, verify that the relevant Hugo settings still match the current Wowchemy structure.

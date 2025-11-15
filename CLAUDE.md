# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an HOA (Homeowners Association) Runbook documentation project built with MkDocs. The repository provides documentation and procedures for HOA management and operations.

## Development Commands

### MkDocs Commands
- `mkdocs serve` - Start the live-reloading documentation server (typically runs on http://127.0.0.1:8000)
- `mkdocs build` - Build the static documentation site (outputs to `site/` directory)
- `mkdocs new [dir-name]` - Create a new MkDocs project
- `mkdocs -h` - Show help for MkDocs commands

## Architecture

### Documentation Structure
- `mkdocs.yml` - MkDocs configuration file defining site metadata, navigation, and theme settings
- `docs/` - Contains all markdown documentation files
  - `docs/index.md` - Homepage/landing page for the documentation site

### Content Organization
Documentation pages should be created as markdown (.md) files in the `docs/` directory. The navigation structure is controlled by the `nav` section in `mkdocs.yml` (when configured).

## Working with This Codebase

When adding new documentation:
1. Create markdown files in the `docs/` directory
2. Update `mkdocs.yml` to configure navigation, theme, and plugins as needed
3. Use `mkdocs serve` to preview changes locally before committing
4. Run `mkdocs build` to verify the site builds successfully

# AGENTS.md

## Repository Purpose

This is a **documentation-only repository** for the [Choreo VS Code extension](https://marketplace.visualstudio.com/items?itemName=WSO2.choreo). It contains no source code, build system, or tests. The actual extension source code lives in the upstream WSO2 repository.

- **Upstream**: https://github.com/wso2/choreo-vscode
- **License**: Apache 2.0 (WSO2 LLC)

## Repository Structure

- `README.md` — Main project page with feature list, getting started guide, and screenshots
- `docs/choreo-extension/` — Documentation and screenshots for the main Choreo extension
  - `images/v2/` — Current (v2) screenshots
  - `release-notes/` — Release notes with version-specific screenshots
- `docs/api-chat-extension/` — Documentation and images for the API Chat extension feature
- `issue_template.md` / `pull_request_template.md` — GitHub contribution templates

## Contribution Conventions

**PR template** requires: Purpose, Goals, Approach, User Stories, Release Note, Documentation links, Security checks (secure coding standards, FindSecurityBugs, no secrets), and Automation test details.

**Issue template** requires: Description, Affected Product Version, OS/environment details, and Steps to reproduce.

## Working in This Repo

All changes here are documentation changes (Markdown files, images, screenshots). There are no build or lint commands. When adding or updating screenshots, place them in the appropriate `docs/` subdirectory following the existing structure.

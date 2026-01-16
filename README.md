# Demo Repository 2

This is a test repository for demonstrating the action-version-updater tool.

## Workflows

This repository contains 5 workflow files:
- `ci.yml` - CI workflow (public actions only)
- `release.yml` - Release workflow (public + custom actions)
- `deploy.yml` - Deploy workflow (custom actions only)
- `security.yml` - Security scanning (public actions only)
- `codeql.yml` - CodeQL analysis (public + custom actions)

## Purpose

Used to test automatic updates of GitHub Actions versions from tags to commit SHAs across multiple workflow files.

# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a GitHub Actions testing repository with a basic CI workflow configuration. The codebase contains only essential GitHub Actions setup files.

## GitHub Actions Workflow

The repository has one workflow file: `.github/workflows/blank.yml:3`

Key workflow characteristics:
- Triggered on push/PR to main branch and manual dispatch
- Sets environment variables from JSON using jq (line 29)
- Contains a malformed JSON string that sets GREMLIN_TEST_HOST and FOO variables
- Runs basic shell commands for demonstration

## Architecture

Minimal repository structure focused on GitHub Actions experimentation:
- No build tools, package managers, or test frameworks
- No source code files beyond workflow configuration
- Single README with repository title only
# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Status

This repository is in its initial state. No build system, dependencies, or application code have been added yet.

## Repository

- GitHub: git@github.com:RainyWang103/app-with-claude.git
- Branch: `main`

# Security rules
- NEVER read or access /mnt/c/, /mnt/d/, or any /mnt/ path
- NEVER read .env, .env.*, secrets/, credentials/ files
- NEVER push directly to main or master branch
- NEVER use --force or -f with git push
- NEVER run curl, wget, nc, or ncat
- NEVER use sudo
- ALWAYS create a feature branch for changes
- ALWAYS run tests before opening a PR
- NEVER store secrets as files — use environment variables only
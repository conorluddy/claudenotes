# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository serves as a knowledge base for Claude Code development, containing:
- Notes: General findings, tips, and observations
- Prompts: Useful prompts and prompt patterns
- Hooks: Custom shell commands and automation scripts
- Commands: Common CLI commands and workflows
- Issues: Known issues, workarounds, and solutions

## Repository Structure

```
claudenotes/
├── Notes/          # General findings and tips
├── Prompts/        # Useful prompts and patterns
├── Hooks/          # Shell commands and automation
├── Commands/       # CLI commands and workflows
└── Issues/         # Known issues and solutions
```

## Development Notes

This is a documentation repository with markdown files. Each directory contains:
- README.md explaining the directory's purpose and organization
- Individual files documenting specific findings, prompts, or solutions

No build system or testing framework is required - this is a static documentation repository.

## Git Workflow

As per user preferences:
- Never push directly to main branch
- Use git-flow methodology with feature branches and PRs
- Main branch represents production releases

## Maintenance Guidelines

- When adding new content, keep the main TOC in sync
- The repo base URL is "https://github.com/conorluddy/claudenotes" for any deep links
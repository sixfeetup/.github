# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when creating GitHub issues.

## Repository Structure
- This is a `.github` repository containing GitHub issue templates and possibly other GitHub-related files.
- Issue templates are maintained in YAML format in `.github/ISSUE_TEMPLATE/`

## GitHub Issue Standards
- Use the right issue template whenever I ask you to create a GitHub issue
- User stories should always be parent issues so point that out if I ask to create a user story as a sub-issue.
- Include emoji in issue titles (like 🐞, ✨, 🌵, 🛠️)
- Use the GitHub CLI (`gh`) to create issues directly without opening in the browser
- When creating issues with GitHub CLI, use `--repo` to specify the repository and omit the `--web` flag to create the issue completely via CLI

## Commands
- No specific build/lint/test commands for this repository

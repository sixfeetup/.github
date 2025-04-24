# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when creating GitHub issues.

## Repository Structure
- This is the special GitHub `.github` repository containing GitHub issue templates and possibly other GitHub-related files for the whole organization.
- The repository contains hidden directories starting with `.` (like `.github/`)
- When searching for files, always include hidden files and directories
- Issue templates are maintained in YAML format in `.github/ISSUE_TEMPLATE/`

## GitHub Issue Standards
- When creating GitHub issues for any SixFeetUp repository, use the templates from THIS repository (dot-github)
- Available templates:
  - User Story: `.github/ISSUE_TEMPLATE/user_story.yml`
  - Task: `.github/ISSUE_TEMPLATE/task.yml`
  - Bug Report: `.github/ISSUE_TEMPLATE/bug_report.yml`
  - Spike: `.github/ISSUE_TEMPLATE/spike.yml`
- Extract template fields directly from these local YAML files, not from remote repositories
- Use the right issue template whenever I ask you to create or edit a GitHub issue
- User stories should always be parent issues so point that out if I ask to create a user story as a sub-issue
- Include emoji in issue titles (like 🐞, ✨, 🌵, 🛠️) matching the template emoji
- Use the GitHub CLI (`gh`) to create issues directly without opening in the browser
- When creating issues with GitHub CLI, use `--repo` to specify the repository and omit the `--web` flag to create the issue completely via CLI
- Format the issue body according to the template's structure and fields

## Commands
- No specific build/lint/test commands for this repository

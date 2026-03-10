# AGENTS.md

This file provides guidance to AI coding agents working within the SixFeetUp organization's GitHub infrastructure.

## Project Overview

This repository (dot-github) serves as the organization's centralized `.github` repository, containing:
- GitHub issue templates for all SixFeetUp repositories
- Organization-wide GitHub configuration

## Repository Structure

### Directory Layout
- `.github/` - Hidden directory containing GitHub configuration
- `.github/ISSUE_TEMPLATE/` - YAML-formatted issue templates

### Issue Templates
- Spike: `.github/ISSUE_TEMPLATE/spike.yml`
- Plan: `.github/ISSUE_TEMPLATE/plan.yml`
- User Story: `.github/ISSUE_TEMPLATE/user_story.yml`
- Task: `.github/ISSUE_TEMPLATE/task.yml`
- Bug Report: `.github/ISSUE_TEMPLATE/bug_report.yml`
- Documentation: `.github/ISSUE_TEMPLATE/documentation.yml`

### Issue Workflow & Hierarchy
- The issue workflow is: spike -> plan -> story -> task
- Plans are standalone issues that link to spikes upstream and stories/tasks downstream (not parent issues)
- The only sub-issue nesting is: User Story (parent) -> Task (child). Max 2 levels.
- All other relationships (spike->plan, plan->story, cross-story ordering) use soft links in the dependencies field

### Important Notes
- Always include hidden files and directories when searching
- This is a special GitHub `.github` repository that applies organization-wide

## Commands

No specific build, lint, or test commands are required for this repository.

## Code Style & Conventions

- Follow standard Markdown formatting
- Use clear hierarchical heading structure
- Employ backticks for command-line syntax
- Maintain consistency with existing documentation patterns

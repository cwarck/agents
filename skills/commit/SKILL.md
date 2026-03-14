---
name: commit
description: Use this skill to make git commits
---

Create a git commit following the Conventional Commits spec.

## Format

`<type>(<scope>): <description>`

### Types

- feat: a new feature
- fix: a bug fix
- refactor: code changes that are neither feat or fix
- docs: documentation changes
- test: tests changes
- chore: everything else
- `!` after the type for breaking changes

### Scope

The scope is OPTIONAL. Infer it from the file path or affected component. Omit if it's unclear what the scope is.

### Description

Infer the description from the changes and write it in a concise and imperative manner.

## Rules
 
- DO NOT add "Co-Authored-By"
- DO NOT add a commit body
- NEVER push

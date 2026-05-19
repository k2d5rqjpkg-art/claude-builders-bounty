# Skill: Generate Changelog

Generates a structured `CHANGELOG.md` from git history.

## Trigger
User says `/generate-changelog` or asks to generate/update changelog from git commits.

## What it does
1. Runs `bash skills/generate-changelog/changelog.sh` in the repo root
2. The script fetches all commits since the last git tag
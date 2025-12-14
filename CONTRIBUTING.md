# Contributing

Thanks for contributing!

## Quickstart
1) Fork the repo and create a branch.
2) Make focused changes (avoid drive-by refactors).
3) Run: `python scripts/validate_skills.py`
4) Open a PR.

## Skill guidelines
- Skills live under `~/.codex/skills/**/SKILL.md` (Codex discovers them at startup).
- `SKILL.md` must start with YAML frontmatter:
  - `name`: non-empty, <= 100 chars, single line
  - `description`: non-empty, <= 500 chars, single line
- Keep instructions concise; prefer checklists.
- Put long/reference material in `references/`.


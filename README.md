# Skill Craft

Meta-skill for creating and editing agent skills with enforced conventions.

## What it does

- Create new skills from scratch with correct structure
- Modify existing skills (SKILL.md, phases, references)
- Harmonize and standardize skill structure
- Enforce token efficiency, triggering accuracy, and consistent conventions

## Installation

### Recommended (npx)

```bash
# Global (available in all projects)
npx skills add Gustav-Finance/skill-craft -g --all

# Project-level only
npx skills add Gustav-Finance/skill-craft --all
```

### Manual (git clone)

```bash
git clone git@github.com:Gustav-Finance/skill-craft.git ~/skill-craft
ln -sf ~/skill-craft/skills/skill-craft ~/.claude/skills/skill-craft
```

## Usage

```
/skill-craft new
/skill-craft my-existing-skill
```

## Complementary tools

- [anthropics/skill-creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator) — iterative skill creation with evals, benchmarks, and description optimization
- **skill-craft** (this skill) — conventions enforcement, token efficiency, quality standards

## License

Private - Gustav Finance

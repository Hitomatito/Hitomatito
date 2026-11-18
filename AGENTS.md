# AGENTS.md

## What this repo is
- GitHub **profile README** repo (`Hitomatito/Hitomatito`). `README.md` is the entire product — it renders on the user's GitHub profile. There is no application code.
- Projects linked from the README (AmWF, RedmagicCooler, HardWire, etc.) live in their own separate repositories. Do not look for or edit their source here.

## Tooling
- No build, test, lint, formatter, typecheck, or codegen setup. Only `README.md` and `.git` exist — don't hunt for manifests or CI.
- Verification is a manual read of the rendered Markdown/HTML (badges, `<div align>` blocks, stats images).

## Conventions (from established history — preserve)
- No emojis. Clean, professional tone, ASCII-art header, centered `<div align="center">` hero, and `---` section separators. Keep the "Last updated <Month Year>" footer current.
- Badges use shields.io `flat-square` style with cyan (`0891b2`) / orange (`f4a261`) accents.
- Stats images intentionally use the personal Vercel deployment `github-readme-stats-three-theta-27.vercel.app`. Do **not** swap back to the official `github-readme-stats.vercel.app` — that caused loading failures.
- The `top-langs` card sets `exclude_repo=vili-hitcore` on purpose: that repo vendors the full Linux kernel (~1.1 GB, 96% C) and otherwise dominates the account's language bytes, hiding the real Kotlin/Python projects. Do not remove that exclusion.
- AmWF and RedmagicCooler are the primary projects; all others are "best-effort". Preserve that ordering and emphasis when editing project lists.
- Commit messages follow conventional-commit prefixes (`docs:`, `fix:`, `feat:`).

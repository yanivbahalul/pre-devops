# Installed skills

| Skill | Source | Notes |
|---|---|---|
| `taste-skill` | https://github.com/Leonxlnx/taste-skill (tasteskill.dev) | Vendored in full, including `assets/` (photo/icon/scene library) as the skill's own SKILL.md requires. |
| `web-design-guidelines` | https://github.com/vercel-labs/agent-skills/blob/main/skills/web-design-guidelines/SKILL.md | Single-file skill; it fetches the live guideline rules from `vercel-labs/web-interface-guidelines` at review time. |
| `image-to-code` | originally https://github.com/LeonxInx/taste-skill/.../image-to-code-skill/SKILL.md | That path no longer exists in the `Leonxlnx/taste-skill` repo (removed/restructured). Installed from an archived snapshot (2026-10-08) in the community mirror `majiayu000/claude-skill-registry-data`. |
| `awesome-design` | https://github.com/VoltAgent/awesome-design-md | Not shipped as a skill upstream (just a DESIGN.md collection) — added a `SKILL.md` wrapper here; vendors the `design-md/` reference folder (80+ companies). |
| `playwright-cli` | https://github.com/microsoft/playwright-cli | Vendors `skills/playwright-cli/` (SKILL.md + references). Using it for real requires the CLI itself: `npm install -g @playwright/cli@latest`. |

Installed from the skill list shared on 2026-11-06.

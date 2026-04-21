# Agent Anatomy

📊 **[Visual diagrams →](https://agent-anatomy.github.io/graphics/)**

> Ready-to-use boilerplates for every AI coding agent. Clone the one you use, copy the folder into your project, edit, ship.

---

## Agents

| Agent | Config file/folder | Boilerplate |
|-------|--------------------|-------------|
| Claude Code | `.claude/` + `CLAUDE.md` | [agent-anatomy/claude](https://github.com/agent-anatomy/claude) |
| Cursor | `.cursor/rules/` + `.cursorrules` | [agent-anatomy/cursor](https://github.com/agent-anatomy/cursor) |
| OpenAI Codex | `AGENTS.md` | [agent-anatomy/codex](https://github.com/agent-anatomy/codex) |
| Windsurf | `.windsurfrules` | [agent-anatomy/windsurf](https://github.com/agent-anatomy/windsurf) |
| GitHub Copilot | `.github/copilot-instructions.md` | [agent-anatomy/copilot](https://github.com/agent-anatomy/copilot) |
| Aider | `.aider.conf.yml` + `CONVENTIONS.md` | [agent-anatomy/aider](https://github.com/agent-anatomy/aider) |
| Gemini CLI | `GEMINI.md` | [agent-anatomy/gemini](https://github.com/agent-anatomy/gemini) |

---

## How to use

Each repo is a standalone boilerplate. Pick your agent, clone, copy into your project, edit.

```bash
# Example: Claude Code
git clone https://github.com/agent-anatomy/claude.git .claude-boilerplate
cp .claude-boilerplate/CLAUDE.md ./CLAUDE.md
cp -r .claude-boilerplate/.claude ./.claude
rm -rf .claude-boilerplate
```

See each repo's README for agent-specific instructions.

---

## Contribute

Using an agent not listed? Add it.

1. Fork [agent-anatomy/claude](https://github.com/agent-anatomy/claude) as a template
2. Create real, working config files for your agent
3. Open a PR to add it to this index

Every boilerplate should have real files people can use — not just docs.

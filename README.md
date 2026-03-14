# ai-marketplace

A Claude Code plugin marketplace.

## Install

```bash
/plugin marketplace add sethwebster/ai-marketplace
```

## Install a plugin

```bash
/plugin install <plugin-name>@ai-marketplace
```

## Update

```bash
/plugin marketplace update ai-marketplace
```

## Install via AI CLI

If you have the [AI CLI](https://github.com/sethwebster/AI) installed, you can install resources directly:

```bash
ai agents install          # browse & install agents
ai install skills          # browse & install Claude Code skills
ai mcp install             # browse & install MCP servers
ai plugins install <name>  # install a Claude Code plugin
```

## Plugins

<!-- plugins table auto-maintained -->

| Plugin | Description |
|--------|-------------|
| [rock-mcp](https://github.com/sethwebster/rock-mcp) | Documentation crawler — crawl any docs URL and search it instantly |

## MCP Servers

Install via `ai mcp install <name>` or manually with `claude mcp add`.

| Name | Description |
|------|-------------|
| [rock-mcp](./mcp/rock-mcp.json) | Documentation crawler — crawl any docs URL and search it instantly |

## Agents

Custom Claude Code subagents. Install via `ai agents install` or copy a `.md` file into `~/.claude/agents/`.

| Agent | Description |
|-------|-------------|
| [ziggy](./agents/ziggy.md) | Electrobun expert — BrowserWindow/BrowserView, typed RPC, webview tags, build config, distribution, updates, code signing, and cross-platform desktop app development |

## Skills

Claude Code slash-command skills. Install via `ai install skills` or copy a skill directory into `~/.claude/skills/`.

| Skill | Invocation | Description |
|-------|-----------|-------------|
| [spec-print](./skills/spec-print/SKILL.md) | `/spec-print` | Build software from a printspec, or reverse-engineer a printspec from an existing codebase |

## Add a resource

Open a PR or issue.

# Claude Code Config

This repository contains configuration for
[Claude Code](https://code.claude.com/docs/en/overview).

Clone it directly to `~/.claude`, since Claude Code reads
its local config from that directory:

```bash
git clone git@github.com:w0rp/claude-code-config.git ~/.claude
```

If `~/.claude` already exists, back it up or move it first:

```bash
mv ~/.claude ~/.claude.bak
git clone git@github.com:w0rp/claude-code-config.git ~/.claude
```

## What is here

- `settings.json` - Claude Code settings, permissions, sandbox rules, and
  defaults
- `skills/` - custom skills loaded by Claude Code

## Updating

To pull the latest config changes:

```bash
git -C ~/.claude pull
```

## License

This project is released under The Unlicense. See `LICENSE`.

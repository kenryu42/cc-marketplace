# CC Marketplace

A curated bundle of Coding CLI plugins for enhanced productivity, skills, and workflows.

This repository provides a native Codex marketplace and a Claude-compatible marketplace.

## Plugins

### CC Safety Net

**Description:** Block destructive commands and secret access in Coding CLI.

**Categories:** Security

**Install:**

```bash
npx -y cc-safety-net install
```

**What you get:**

- Prevent destructive commands and secret access

**Repository:** https://github.com/kenryu42/cc-safety-net

### Just So You Know

**Description:** A side agent watches longer tasks and passes what it finds to the main agent automatically, with a report of how each note landed.

**Categories:** Productivity

**Install (Claude Code only):**

```
/plugin install just-so-you-know --marketplace kenryu42/cc-marketplace
```

If you already added cc-marketplace, `/plugin install just-so-you-know@cc-marketplace` is enough. If you use the built-in **You should know** plugin, turn it off (`/plugin`) so the two do not both run.

**What you get:**

- A side agent that checks the session about every 6 steps and only speaks up when something clears a high bar
- Findings delivered straight to the main agent as hidden notes, with a toast showing the one-line summary
- A verdict on how the main agent took each note: helped, acknowledged, already aware or no reaction
- `/jsyk` to write and open a page with every note across sessions (`~/.claude/just-so-you-know/report.html`)

**Repository:** https://github.com/kenryu42/just-so-you-know


## License

MIT

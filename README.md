# AITG-hub

AccessIT Group's Claude Code plugin marketplace.

## Add this marketplace

```
/plugin marketplace add AccessITGroup/claude-plugins
```

## Plugins

| Plugin | Description | Repo |
|---|---|---|
| `webapp-testing-checklist` | WSTG-aligned web app pentest checklist and report-generation aid (does not perform testing itself) | [AccessITGroup/webapp-testing-checklist](https://github.com/AccessITGroup/webapp-testing-checklist) |

## Adding a plugin

1. Add the plugin's repo (or a subdirectory in this repo) as a source.
2. Add an entry to the `plugins` array in `.claude-plugin/marketplace.json`.
3. Update this table.
4. Commit and push.

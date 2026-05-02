# jgcosme-plugins

A Claude Code plugin marketplace that aggregates personal plugins by [jgcosme](https://github.com/jgcosme). The plugins themselves live in their own repos; this one only hosts the registry.

## Install

```
/plugin marketplace add jgcosme/claude-plugins
```

Then `/plugin install <name>@jgcosme-plugins` for any of the plugins below.

## Plugins

| Name | Repo | Description |
|---|---|---|
| `obsidian-memory` | [claude-obsidian-memory](https://github.com/jgcosme/claude-obsidian-memory) | Obsidian-backed persistent memory for Claude Code |
| `slack-sessions` | [claude-slack-sessions](https://github.com/jgcosme/claude-slack-sessions) | Drive Claude Code from Slack with one isolated session per thread |

## Versioning

Plugin entries reference the **default branch** of each repo (floating). Updates to a plugin are picked up on the next `/plugin marketplace update`. To pin to a specific tag or commit, add `"ref"` or `"sha"` to that plugin's `source` block in [`.claude-plugin/marketplace.json`](.claude-plugin/marketplace.json).

## License

MIT — see [LICENSE](LICENSE).

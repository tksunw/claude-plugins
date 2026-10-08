# claude-plugins

Marketplace catalog for Tim Kennedy's Claude Code mods and plugins. It holds only the catalog; each plugin lives in its own repo.

```bash
claude plugin marketplace add tksunw/claude-plugins
claude plugin install usage-reporter@tksunw
claude plugin install status-enhanced@tksunw
claude plugin install secret-guard@tksunw
```

Auto-update is off by default for third-party marketplaces. Turn it on for `tksunw` in `/plugin`, or run `claude plugin marketplace update tksunw`. A plugin update is only picked up when its `version` in `.claude-plugin/plugin.json` changes.

| Plugin | Repo |
|---|---|
| usage-reporter | https://github.com/tksunw/usage-reporter |
| status-enhanced | https://github.com/tksunw/status-enhanced |
| secret-guard | https://github.com/tksunw/secret-guard |

To add a plugin, append an entry to `plugins[]` in `.claude-plugin/marketplace.json`.

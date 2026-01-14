# Claude Plugins

A collection of plugins for Claude Code.

## Installation

Add the marketplace to your Claude Code settings (`~/.claude/settings.json`):

```json
{
  "extraKnownMarketplaces": {
    "extra-plugins": {
      "source": {
        "source": "github",
        "repo": "claude-contrib/extra-plugins"
      }
    }
  }
}
```

Then install plugins:

```text
/plugin install <plugin-name>@extra-plugins
```

## Available Plugins

| Plugin                                               | Description                                                  |
| ---------------------------------------------------- | ------------------------------------------------------------ |
| [`agents-context`](plugins/agents-context/README.md) | Enable [AGENTS.md](https://agents.md/) rules for Claude Code |

## License

MIT

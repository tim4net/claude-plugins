# tim4net Claude Code Plugins

A marketplace of Claude Code plugins by Tim Fournet.

## Installation

**Step 1: Add this marketplace**
```
/plugin marketplace add tim4net/claude-plugins
```

**Step 2: Install any plugin**
```
/plugin install rewst-openapi@tim4net
```

Or use the UI: type `/plugin`, go to **Discover**, and browse available plugins.

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [rewst-openapi](https://github.com/tim4net/claude-rewst-integration-factory) | Create, validate, and fix OpenAPI specs for Rewst Custom Integration v2 |

## For Plugin Developers

To add a plugin to this marketplace, add an entry to `.claude-plugin/marketplace.json`:

```json
{
  "name": "your-plugin-name",
  "source": {
    "source": "github",
    "repo": "owner/repo-name"
  },
  "description": "What your plugin does",
  "version": "1.0.0",
  "author": {
    "name": "Your Name"
  }
}
```

The plugin repo must have a valid `.claude-plugin/plugin.json` at its root.

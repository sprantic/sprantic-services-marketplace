# sprantic Services Marketplace (GitHub)

A curated collection of Claude Code plugins for sprantic services.

> This is the **GitHub** branch. For GitLab, use the `gitlab` branch.

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [services](https://github.com/sprantic/sprantic-plugin-services) | Services consulting and delivery workflow |

## Setup

Add to your settings (`.claude/settings.json` for a project, `~/.claude/settings.json` for personal use):

```json
{
  "extraKnownMarketplaces": {
    "sprantic-services-marketplace": {
      "source": {
        "source": "github",
        "repo": "sprantic/sprantic-services-marketplace",
        "ref": "github"
      }
    }
  },
  "enabledPlugins": {
    "services@sprantic-services": true
  }
}
```

# sprantic Services Marketplace (GitHub)

A curated collection of Claude Code plugins for sprantic services.

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [sprantic-services](https://github.com/sprantic/sprantic-plugin-services) | Services consulting and delivery workflow |
| [sprantic-html](https://github.com/sprantic/sprantic-plugin-html-presentation) | Generate single-file HTML presentations in sprantic corporate design |

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

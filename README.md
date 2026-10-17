# ai_tribe marketplace

The catalogue of ai_tribe plugins for Claude. Add it once and every plugin you have access to shows up in Claude, ready to install. New plugins and updates arrive through the same place.

## Before you start

- **Accept your invites.** GitHub emails you an invite to this repo and one to each plugin you have. Nothing installs until they are accepted.
- **Sign this Mac in to GitHub.** The repos are private, so Claude needs your GitHub login to download them. In Terminal: `brew install gh`, then `gh auth login` and `gh auth setup-git`. You only do this once per Mac.

## Add the marketplace

**Claude desktop app**

1. Open **Settings** > **Plugins**.
2. Click **Add custom** and paste `ai-tribe-marketplace/marketplace`.
3. Install the plugins you want, then start a new session so they load.

**Claude Code in the terminal**

```bash
claude plugin marketplace add ai-tribe-marketplace/marketplace
claude plugin install creative-engine@ai-tribe
```

Restart Claude Code afterwards.

## Plugins

| Plugin | What it does | Install name |
|---|---|---|
| [Creative Engine](https://github.com/ai-tribe-marketplace/creative-engine) | Image and video ads for your brand on your own kie.ai account, with a cost quote before every batch | `creative-engine@ai-tribe` |

Each plugin's own README covers its setup and use.

## Updates

Desktop app: update from **Settings** > **Plugins**. Terminal: `claude plugin marketplace update ai-tribe`, then `claude plugin update <install name>`. Each plugin lists its changes in its CHANGELOG.

## Something not working?

- **"Repository not found" or a login prompt:** an invite is not accepted yet, or this Mac is not signed in to GitHub (see Before you start).
- **A plugin is missing from the list:** you do not have access to it yet. Email us.

Questions: [hello@aitribe.com.au](mailto:hello@aitribe.com.au) or [aitribe.com.au](https://aitribe.com.au).

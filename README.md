# ai_tribe marketplace

The catalogue of ai_tribe plugins for Claude. Anyone can add it. Each plugin is private, and you can install the ones you have been given access to. New plugins and updates arrive through the same place.

## Before you start

- **Accept your invite.** GitHub emails you an invite to each plugin you have. It will not install until you accept it.
- **Sign this Mac in to GitHub.** The plugins are private, so Claude needs your GitHub login to download them. In Terminal: `brew install gh`, then `gh auth login` and `gh auth setup-git`. You only do this once per Mac.

## Add the marketplace

**Claude desktop app**

1. Open **Settings** > **Plugins**.
2. Click **Add custom** and paste `ai-tribe-marketplace/marketplace`.
3. Install the plugins you have access to, then start a new session so they load.

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

- **"Repository not found" or a login prompt when installing:** you do not have access to that plugin, its invite is not accepted yet, or this Mac is not signed in to GitHub (see Before you start).
- **Want a plugin you do not have?** Email us.

Questions: [hello@aitribe.com.au](mailto:hello@aitribe.com.au) or [aitribe.com.au](https://aitribe.com.au).

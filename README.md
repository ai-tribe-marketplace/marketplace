# AI Tribe Marketplace

The AI Tribe catalogue of Claude plugins. Add it once and every AI Tribe plugin you have access to appears in Claude.

## Add the marketplace

You need an invite to this repo and to each plugin you bought. Accept the invite emails from GitHub first.

**Claude desktop app:** **Settings** > **Plugins** > **Add custom**, paste `ai-tribe-marketplace/marketplace`, then install the plugins you want.

**Claude Code in the terminal:**

```bash
claude plugin marketplace add ai-tribe-marketplace/marketplace
claude plugin install creative-engine@ai-tribe
```

The repos are private, so this Mac must be signed in to GitHub: `brew install gh`, then `gh auth login` and `gh auth setup-git`.

## Plugins

| Plugin | Does |
|---|---|
| [creative-engine](https://github.com/ai-tribe-marketplace/creative-engine) | Image and video ads on your own kie.ai key |

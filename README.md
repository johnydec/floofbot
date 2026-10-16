# fluffbots

Plush, animated companions that sit above the Claude Code prompt in cmux, Ghostty, kitty and WezTerm.

## Install

At the Claude Code prompt (pick any body + colour below):

```
/plugin install fluffbot-clay-classic --marketplace johnydec/fluffbots
```

From a shell: `claude plugin install fluffbot-clay-classic --marketplace johnydec/fluffbots`

## Presets

- `fluffbot-clay-blob`
- `fluffbot-clay-classic`
- `fluffbot-clay-round`
- `fluffbot-clay-tall`
- `fluffbot-cream-blob`
- `fluffbot-cream-classic`
- `fluffbot-cream-round`
- `fluffbot-cream-tall`
- `fluffbot-graphite-blob`
- `fluffbot-graphite-classic`
- `fluffbot-graphite-round`
- `fluffbot-graphite-tall`
- `fluffbot-lilac-blob`
- `fluffbot-lilac-classic`
- `fluffbot-lilac-round`
- `fluffbot-lilac-tall`
- `fluffbot-mint-blob`
- `fluffbot-mint-classic`
- `fluffbot-mint-round`
- `fluffbot-mint-tall`
- `fluffbot-rose-blob`
- `fluffbot-rose-classic`
- `fluffbot-rose-round`
- `fluffbot-rose-tall`
- `fluffbot-sky-blob`
- `fluffbot-sky-classic`
- `fluffbot-sky-round`
- `fluffbot-sky-tall`

## Security

Every preset is a zip attached to the `packs-v0.1.0` release and pinned by SHA-256 in
`.claude-plugin/marketplace.json`; Claude Code verifies it on every download and refuses a mismatch.
The plugin only observes Claude Code's events and draws pre-rendered frames above the prompt:
no network, no processes, no file writes.

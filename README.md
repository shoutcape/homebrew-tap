# Shoutcape Homebrew Tap

Homebrew formulas for Shoutcape command-line tools.

| Software | Description | Install |
| --- | --- | --- |
| [TreeMan](https://github.com/shoutcape/TreeMan) | Git worktree management CLI | `brew install shoutcape/tap/treeman` |

## TreeMan

TreeMan creates isolated Git worktrees and configures them for local development.

```bash
brew install shoutcape/tap/treeman
```

Add its shell wrappers after installation:

```bash
eval "$(treeman init zsh)"
```

Read the [TreeMan documentation](https://github.com/shoutcape/TreeMan#readme) for requirements and installation details.

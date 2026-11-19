# rustket-bits

Official package definitions for the Rustket package manager.

## Available bits

- `rustket` - Rustket CLI
- `ripgrep` - ripgrep text search utility

Install ripgrep with:

```sh
rustket install ripgrep
```

Rustket links installed commands under their bit names, so this bit is exposed
as `ripgrep` in `~/.rustket/bin`.

# tmux configuration

Cheat Sheet - https://tmuxcheatsheet.com/

## Useful commands

- **Prefix**: `C-Space`
- **Standard bindings**
  - `z` - Toggle zoom pane
  - `&` - Close window
  - `%` - Split horizontal
  - `"` - Split vertical
  - `,` - Rename window
  - `$` - Rename session
  - `w` - Window chooser (`x` to kill, `,` to rename)
  - `o` - Next pane
  - `;` - Toggle last active pane
- **Custom bindings**
  - `r` - Reload configuration
  - `O` - Previous pane
  - `\` - 3-pane layout (60/40 split + vertical)
  - `|` - Keep only pane 1 (kill others)
  - `x` - Kill current pane (no confirm)
  - `X` - Kill current session
  - `T` - Set pane title (updates window name)
  - `k` - Clear and `>` current pane
  - `K` - Clear and `>` right panels (panes 2 and 3)
  - `y` - Floating terminal popup (70%)
  - `u` - Toggle persistent scratchpad (`popup-win`) (experimental)

## Reload configuration

To reload the tmux configuration, you can press `Prefix` + `r` or run:

```sh
tmux source-file ~/.tmux.conf
```

## Setup

- **Prefix**: `C-Space`
- **Mouse**: Enabled
- **Indexing**: Windows and Panes start at `1`, renumbered on close.
- **Naming**: Automatic renaming enabled; manual pane titles (`Prefix T`) override window names.

This configuration is located in `~/.config/tmux/`.
The `~/.tmux.conf` file is symlinked to `~/.config/tmux/.tmux.conf`.


## Info

License: Apache OR MIT

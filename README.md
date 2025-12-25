# tmux configuration

Cheat Sheet - https://tmuxcheatsheet.com/

## Useful commands

- Standard command
  - `Prefix` `&` - close window
  - `Prefix` `%` - (with shift), split horizontal
  - `Prefix` `"` - (with shift), split vertical
- JC Custom
  - `Prefix` `r` - Reload configuration
  - `Prefix` `\` - custom 3-pane layout (60/40 split + vertical)
  - `Prefix` `|` - kill right panels (panes 2 and 3)
  - `Prefix` `x` - kill current session (unbound the default `x` to close pane)
  - `Prefix` `C` - clear right panels (panes 2 and 3)

## Reload configuration

To reload the tmux configuration, you can press `Prefix` + `r` or run:

```sh
tmux source-file ~/.tmux.conf
```


## Setup

This configuration is located in `~/.config/tmux/`.
The `~/.tmux.conf` file is symlinked to `~/.config/tmux/.tmux.conf`.

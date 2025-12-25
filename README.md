# tmux configuration

Cheat Sheet - https://tmuxcheatsheet.com/

## Useful commands

- Standard command
  - `Prefix` + `&` - close window
  - `Prefix` + `%` - (with shift), split horizontal
  - `Prefix` + `"` - (with shift), split vertical
- JC Custom
  - `Prefix` + `|` - custom 3-pane layout (60/40 split + vertical)
  - `Prefix` + `X` - kill current session
  - `Prefix` + `C` - kill all unattached sessions

## Reload configuration

To reload the tmux configuration, you can press `Prefix` + `r` or run:

```sh
tmux source-file ~/.tmux.conf
```


## Setup

This configuration is located in `~/.config/tmux/`.
The `~/.tmux.conf` file is symlinked to `~/.config/tmux/.tmux.conf`.

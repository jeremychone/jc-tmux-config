# tmux configuration

Cheat Sheet - https://tmuxcheatsheet.com/

## Useful commands

- Standard command
  - `C-Space z` - Toggle current pane full screen / back to same
  - `C-Space &` - close window
  - `C-Space %` - (with shift), split horizontal
  - `C-Space "` - (with shift), split vertical
  - `C-Space ,` - rename current window
  - `C-Space $` - rename current session
  - `C-Space w` - Window chooser 
    - `C-Space ,` to rename
    - `C-Space &` kill window
  - `C-Space o` - Next Pane
  - `C-Space ;` - Last Active Pane (toggle)
- JC Custom
  - `C-Space r` - Reload configuration
  - `C-Space O` - Prev Pane
  - `C-Space \` - custom 3-pane layout (60/40 split + vertical)
  - `C-Space |` - kill right panels (panes 2 and 3)
  - `C-Space x` - kill current pane (no confirmation)
  - `C-Space X` - kill current session
  - `C-Space C` - clear right panels (panes 2 and 3)
  - `C-Space k` - clear current pane (clear + \ + C-l)

## Reload configuration

To reload the tmux configuration, you can press `Prefix` + `r` or run:

```sh
tmux source-file ~/.tmux.conf
```


## Setup

This configuration is located in `~/.config/tmux/`.
The `~/.tmux.conf` file is symlinked to `~/.config/tmux/.tmux.conf`.

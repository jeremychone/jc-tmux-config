# tmux configuration

Cheat Sheet - https://tmuxcheatsheet.com/

## Useful commands

- Standard command
  - `C-b z` - Toggle current pane full screen / back to same
  - `C-b &` - close window
  - `C-b %` - (with shift), split horizontal
  - `C-b "` - (with shift), split vertical
  - `C-b ,` - rename current window
  - `C-b $` - rename current session
  - `C-b w` - Window chooser 
    - `C-b ,` to rename
    - `C-b &` skill window
  - `C-b o` - Next Pane
  - `C-b ;` - Last Active Pane (toogle)
- JC Custom
  - `C-b r` - Reload configuration
  - `C-b O` - Prev Pane
  - `C-b \` - custom 3-pane layout (60/40 split + vertical)
  - `C-b |` - kill right panels (panes 2 and 3)
  - `C-b x` - kill current session (unbound the default `x` to close pane)
  - `C-b C` - clear right panels (panes 2 and 3)
  - `C-b K` - clear current pane (clear + \ + C-l)

## Reload configuration

To reload the tmux configuration, you can press `Prefix` + `r` or run:

```sh
tmux source-file ~/.tmux.conf
```


## Setup

This configuration is located in `~/.config/tmux/`.
The `~/.tmux.conf` file is symlinked to `~/.config/tmux/.tmux.conf`.

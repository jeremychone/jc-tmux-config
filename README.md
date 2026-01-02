# Jeremy Chone TMUX Config

Just sharing, cherry-pick what you need.

Related repos:
- [jc-zed-config](https://github.com/jeremychone/jc-zed-config)
- [jc-zed-tasks](https://github.com/jeremychone/jc-zed-tasks)
- [jc-tmux-config (this one)](https://github.com/jeremychone/jc-tmux-config)
- [jc-alacritty-config](https://github.com/jeremychone/jc-tmux-config)

## Setup

- Setup host terminal with a [Nerd Fonts](https://www.nerdfonts.com/)
- Copy or git clone into `~/.config/tmux/`
- Edit `~/.tmux.conf` with:
```
source-file ~/.config/tmux/tmux-main.conf
```

Important: If you use TMUX Plugin Manager, add the `set -g @plugin...` and `run '~/.tmux/plugins/tpm/tpm'` lines in `~/.tmux.conf`. They don’t really work in `~/.config/tmux/tmux.conf`.

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

To reload the tmux configuration, press `Prefix` + `r` or run:

```sh
tmux source-file ~/.tmux.conf
```

## Setup

- **Prefix**: `C-Space`
- **Mouse**: Enabled
- **Indexing**: Windows and panes start at `1`, renumbered on close.
- **Naming**: Automatic renaming enabled; manual pane titles (`Prefix T`) override window names.

This configuration is located in `~/.config/tmux/`.
The `~/.tmux.conf` file is symlinked to `~/.config/tmux/.tmux.conf`.

## Others

- License: Apache OR MIT
- TMUX Cheat Sheet - https://tmuxcheatsheet.com/

[This repo](https://github.com/jeremychone/jc-tmux-config)

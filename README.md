# Melange Tmux Theme

A powerline-style tmux theme based on the [melange-nvim](https://github.com/savq/melange-nvim) colorscheme.

## Features

- **Session name on the left** with powerline styling
- **Window list** showing index and name
- **Prefix key indicator** - session name changes from cyan to red when prefix is pressed
- **No right-side clutter** - clean, minimal design
- **Melange color palette** - warm, cozy colors that match your neovim theme

## Installation

1. Source the theme in your `~/.tmux.conf`:
   ```bash
   source-file /path/to/melange-tmux.conf
   ```

2. Reload tmux configuration:
   ```bash
   tmux source-file ~/.tmux.conf
   ```

## Color Scheme

The theme uses the melange dark palette:
- Background: `#292522`
- Foreground: `#C1A78E` 
- Session name: `#89B3B6` (cyan) / `#D47766` (red when prefix pressed)
- Active window: `#EBC06D` (yellow)
- Inactive windows: `#34302C` (light background)

## Customization

You can modify colors by editing the variables at the top of `melange-tmux.conf`. All colors are based on the melange palette for consistency with your neovim setup.
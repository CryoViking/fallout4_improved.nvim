# WezTerm Installation

There are two main ways to use this theme with WezTerm.

## Method 1: Direct `require` (Recommended)

This is the simplest method. Add the following line to your `wezterm.lua` configuration file, making sure to replace `/path/to/this/repo` with the actual absolute path to where you have cloned this repository.

```lua
local wezterm = require 'wezterm'
local config = wezterm.config_builder()

-- ... your other config ...

config.colors = require '/path/to/this/repo/extras/wezterm/fallout4_improved_default.lua'

-- ...

return config
```

## Method 2: Symlink to WezTerm `colors` directory

You can also symlink the theme file into WezTerm's `colors` directory.

1.  Find your WezTerm config directory. It's usually `~/.config/wezterm/`.
2.  Create a `colors` directory inside it if it doesn't exist:
    ```sh
    mkdir -p ~/.config/wezterm/colors
    ```
3.  Symlink our theme file into that directory. Make sure to use the absolute path to this repository.
    ```sh
    ln -s /path/to/this/repo/extras/wezterm/fallout4_improved_default.lua ~/.config/wezterm/colors/
    ```
4.  Now you can set the theme by name in your `wezterm.lua`:
    ```lua
    config.color_scheme = 'fallout4_improved_default'
    ```

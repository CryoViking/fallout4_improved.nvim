# Fish Shell Theme Installation

To use this theme, you need to copy the `.theme` file to your Fish shell's themes directory and then set it.

1.  Find your Fish shell configuration directory. It's usually `~/.config/fish/`.
2.  Create a `themes` directory inside it if it doesn't exist:
    ```sh
    mkdir -p ~/.config/fish/themes
    ```
3.  Copy our theme file into that directory. Make sure to use the absolute path to this repository:
    ```sh
    cp /path/to/this/repo/extras/fish/fallout4_improved_default.theme ~/.config/fish/themes/
    ```
4.  Then, set the theme in your `~/.config/fish/config.fish` file (or directly in your terminal for a temporary change):
    ```fish
    set fish_theme fallout4_improved_default
    ```
5.  Restart your fish shell to see the changes.
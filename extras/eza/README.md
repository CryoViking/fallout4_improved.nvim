# Eza Theme Installation

To use this theme, you need to place the `theme.yml` file in your `eza` configuration directory.

1.  Find your `eza` configuration directory. It's usually `~/.config/eza/`.
2.  Create this directory if it doesn't exist:
    ```sh
    mkdir -p ~/.config/eza/
    ```
3.  Copy our theme file into that directory. Make sure to use the absolute path to this repository:
    ```sh
    cp /path/to/this/repo/extras/eza/theme.yml ~/.config/eza/
    ```
4.  **Important:** `eza`'s environment variables (`EZA_COLORS`, `LS_COLORS`) take precedence over `theme.yml` files. If you have these variables set, you may need to unset them (e.g., `unset EZA_COLORS`) to ensure the `theme.yml` colors are applied.
5.  The theme will be applied automatically the next time you run `eza`.

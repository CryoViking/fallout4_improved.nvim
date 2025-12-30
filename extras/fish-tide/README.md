# Fallout 4 Improved Tide Theme

This directory contains the configuration for the Fallout 4 Improved theme for Tide, a popular prompt for the Fish shell.

## Installation

1.  **Place the theme file:**
    The `fallout4_improved_tide.fish` file needs to be sourced by your Fish shell. The recommended way to do this is to add a line to your `~/.config/fish/config.fish` file.

    Open your `config.fish` file:
    ```bash
    nvim ~/.config/fish/config.fish
    # or code ~/.config/fish/config.fish
    ```

    Add the following line to source the theme. **Make sure to replace `/path/to/your/project/fallout4_improved.nvim` with the actual absolute path to this project on your system.**
    ```fish
    source /path/to/your/project/fallout4_improved.nvim/extras/fish-tide/fallout4_improved_tide.fish
    ```

2.  **Configure Tide (if necessary):**
    If you haven't configured Tide before, or if you want to ensure it's using the "Custom" theme where these settings take effect, run the Tide configuration wizard:
    ```bash
    tide configure
    ```
    During the wizard, you may be prompted to select a theme style. Choose the "Custom" or "Manual" option if available, to ensure your sourced `fallout4_improved_tide.fish` settings are used.

3.  **Restart Fish Shell:**
    Close and reopen your terminal, or simply type `fish` to start a new Fish session.

Your Fish prompt should now be styled with the Fallout 4 terminal-inspired colors!

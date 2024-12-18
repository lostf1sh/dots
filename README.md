## Cool Hyprland Setup

### screenshot:
![desktop](https://telegra.ph/file/ad139752c268f5ee38e9d.png)\

### how to use:
- install paru (an aur helper):
    ```bash
    sudo pacman -S --needed base-devel git
    git clone https://aur.archlinux.org/paru-bin.git
    cd paru-bin
    makepkg -si
    cd
    rm -rf paru-bin
    ```
- clone the repo:
    ```bash
    git clone https://github.com/lostf1sh/dotfiles.git
    cd dotfiles
    ```
- run the install script:
    ```bash
    chmod u+x install.sh
    ./install.sh
    ```
- *NOTE:*\
    you have to edit your monitor name in hyprland configuration files\
    check your monitor name by running:
    ```bash
    hyprctl monitors all
    ```

## special thanks

[ArchLainux](https://github.com/archlainux) - For Cool Hyprland Setup

[hyprland](https://github.com/hyprwm/Hyprland) - For Cool WM

[catppuccin](https://github.com/catppuccin) - For Cool Theme

[nvchad](https://github.com/NvChad/NvChad/tree/v2.0) - For Cool Base Config

[dreamsofcode-io](https://github.com/dreamsofcode-io) - For Cool NVChad Setup

[newmanls](https://github.com/newmanls/rofi-themes-collection) - For Cool Rofi Style

[jluttine](https://github.com/jluttine/rofi-power-menu) - For Cool Rofi Power Script

[kangie](https://github.com/Kangie/sddm-sugar-candy) - for Cool SDDM Theme

[archwiki members](https://wiki.archlinux.org/title/Hyprland) - For Cool Mako Scripts From Wiki Users

[doprz](https://github.com/doprz/dipc) - For Cool dipc :3

# How to use this piece of crap

# Template manual

# Config manual

## Structure of config
1. Data - Your source of colors and other shit (GUI MODE avaialble).
2. Targets - Well, stuff whose colors you want to change.
3. Restarts - Programs to restart after applying a theme (Optional).

## At first, you need to set up your config:

1. Open ~/.config/muscat/config.jsonc
2. Enter your settings. For reference:

```json
{
  "data": "~/dotfiles/.config/muscat/themes/catppuccin.json",
    
  "targets": [
    "~/dotfiles/.config/waybar/config.jsonc",
    "~/dotfiles/.config/waybar/style.css",
    "~/dotfiles/.config/swaync/style.css",
    "~/dotfiles/.config/cava/config",
    "~/dotfiles/.config/starship.toml",
    "~/dotfiles/.config/kitty/kitty.conf",
    "~/dotfiles/.config/gtk-3.0/gtk.css",
    "~/dotfiles/.config/gtk-4.0/gtk.css",
    "~/dotfiles/.config/vesktop/themes/theme.css",
    "~/dotfiles/.config/zed/settings.json",
    "~/dotfiles/.config/zed/themes/base16.json",
    "~/dotfiles/.config/hypr/hyprland.conf",
    "~/dotfiles/.config/alacritty/alacritty.toml",
    "~/dotfiles/.config/rofi/theme.rasi"
  ],
  
  "restarts": [
    "waybar",
    "zed",
    "swaync"
  ]
}
```

# How to use GUI MODE
## To enable the graphical shell, you have to run this programm with --gui argument.
In GUI mode RGBT looks for themes at ~/.config/muscat/themes

![screenshot](assets/preview.png)

# Notice about CLI MODE
## In CLI mode, "restarts" field is still optional, but you must fill "data" field.
### ЛИИИНУУУКС КАКАШКООО, ШИИНДОООУС 10 ЛУУУЧШЕЕЕЕЕЕЕЮФЩВЫТАШГФКИШЩНЫИКГЩРИЫКВ

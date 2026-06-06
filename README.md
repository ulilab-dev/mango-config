# mangowm-config

### must install
```
rofi swaybg hyprlock waybar wlogout fish kitty polkit-gnome starship hyprshot dunst power-profiles-daemon wl-clipboard wl-clip-persist cliphist 

#MediaPlayer

celluloid
```

### fix dolphin defaults apps
```
sudo pacman -S kde-cli-tools
sudo pacman -S archlinux-xdg-menu
```

### set kitty for defaults terminal on dolphin
edit `/etc/xdg/kdeglobals`

add this line
```
[General]
TerminalApplication=kitty
TerminalService=kitty.desktop
```

### Font 

```
JetBrainsMono Nerd Font
```

### set cursor
edit `/usr/share/icons/default/index.theme`
```
[Icon Theme]
Inherits=Simp1e

```

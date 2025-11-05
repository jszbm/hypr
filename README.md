# My [hyprland](https://github.com/hyprwm/Hyprland) configuration files

### Dependencies:
```
sudo pacman -S kitty dolphin rofi hyprpicker hyprpolkitagent
```

# Input method:
```
sudo pacman -S fcitx5 fcitx5-mozc fcitx5-gtk fcitx5-qt fcitx5-configtool
```

### Installation:
```
cd ./.config/
git clone git@github.com:jszbm/hypr.git
cd ./hypr/
```

Laptop:
```
mv hyprland-laptop.conf hyprland.conf && rm hyprland-desktop.conf
```

Desktop:
```
mv hyprland-desktop.conf hyprland.conf && hyprland-laptop.conf
```

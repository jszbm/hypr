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
cd
mkdir config
cd ./config/
git clone git@github.com:jszbm/hypr.git
cd ..
cp -r ./config/hypr ./.config/hypr/
cd ./.config/hypr
```

Laptop:
```
cp hyprland-laptop.conf hyprland.conf
```

Desktop:
```
cp hyprland-desktop.conf hyprland.conf
```

# Overview and automatic installation
Collection of dot config files for hyprland for HDReady displays with a simple install script for a fresh Arch linux with yay

![image](https://user-images.githubusercontent.com/122752743/229296919-466b6798-0ada-4070-b15a-749712dc1add.png)



Copy the yay git and install it, then copy this repo to /opt/ and make it owned by you (NOT ROOT), after that use the attached script "set-hypr" to install everything automatically.

```
chmod +x set-hypr && ./set-hypr
```

# Manual Installation
Grab the config files and install packages with this commnad
```
yay -S hyprland-bin kitty waybar-hyprland \
    swaybg swaylock-effects wofi wlogout mako thunar \
    ttf-jetbrains-mono-nerd noto-fonts-emoji \
    polkit-gnome python-requests starship \
    swappy grim slurp pamixer brightnessctl gvfs \
    bluez bluez-utils lxappearance xfce4-settings \
    dracula-gtk-theme dracula-icons-git xdg-desktop-portal-hyprland-git
```


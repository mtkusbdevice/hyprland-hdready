# Overview and automatic installation
Collection of dot config files for hyprland for HDReady displays with a simple install script for a fresh Arch linux with yay

![image](https://github.com/vidowner/hyprland-hdready/assets/122752743/93760215-2f98-4101-a7f9-b929abeee163)

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

# Keybindings

```SUPER + SPACE``` - Show the graphicall app launcher; 
```SUPER + Shift + S``` - Select area for screenshot; 
```SUPER + RETURN``` - Launch kitty (default terminal); 
```ALT + F4``` - Close focused window; 
```SUPER + E``` - Launch Thunar (GUI File Manager); 
```Shift + Alt``` - Switch between keyboard layouts (Default: us,ru); 
```SUPER + L``` - Lock the screen; 
```SUPER + V``` - Toggle window floating; 
```SUPER + M``` - Show power/logout menu; 
```SUPER + Shift + M``` - Exit Hyprland all together no (force quit Hyprland); 
```SUPER + P``` - psuedo, dwindle; 
```SUPER + J``` - togglesplit, dwindle; 

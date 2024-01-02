# dots-hyprland-winter

This hyprland configuration based on https://github.com/AmadeusWM/dotfiles-hyprland
![image](https://github.com/vesnaIwakura18/dots-hyprland-winter/assets/112858545/781efc50-61ce-4e5e-bd1d-cc6184734824)
# Installation
## Step 1. Install Hyprland
Just run `sudo pacman -S hyprland`
## Step 2. Install dependencies
Run following command: `sudo pacman -S hyprland-git nerd-fonts-complete-starship wofi dunst jq eww-wayland swayidle swaylock-effects-git swaylockd sway-audio-idle-inhibit-git bc pamixer light-git papirus-icon-theme playerctl cava kitty xdg-desktop-portal-wlr grim slurp wl-clipboard socat swappy cliphist hyprpicker nm-connection-editor dictd wl-clip-persist-git blueberry`
## Step 3. Configure the directories
Clone the repo, then move all directories to the `/.config/hypr` directory by running following command: `cp -r ./* ~/.config/hypr`. Make sure that hyprland.conf was overwrited
## Step 4. Reload
Run `hyprctl reload`

#

Follow https://wiki.hyprland.org/ for more information.

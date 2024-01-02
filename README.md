# dots-hyprland-winter

This hyprland configuration based on https://github.com/AmadeusWM/dotfiles-hyprland

# Installation
## Step 1. Install Hyprland
Just run `sudo pacman -S hyprland`
## Step 2. Install dependencies
Run following command: `sudo pacman -S hyprland-git nerd-fonts-complete-starship wofi dunst jq eww-wayland swayidle swaylock-effects-git swaylockd sway-audio-idle-inhibit-git bc pamixer light-git papirus-icon-theme playerctl cava kitty xdg-desktop-portal-wlr grim slurp wl-clipboard socat swappy cliphist hyprpicker nm-connection-editor dictd wl-clip-persist-git blueberry`
## Step 3. Configuring the directories
Clone the repo, then move all directories to the `/.config/hypr` directory by running following command: `cp -r ./* ~/.config/hypr`. Make sure that hyprland.conf was overwrited
## Step 4. Reloading
Run `hyprctl reload`

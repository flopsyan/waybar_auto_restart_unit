# Installation Instructions
1. **Download the file**

2. **Move it to `~/.config/systemd/user/`**

3. **Reload the global systemd (user-)units and start and enable the service**</br>
   `systemctl --user daemon-reload`</br>
   `systemctl --user enable --now waybar-autostart.service`

4. **Remove existing Waybar autostart lines, if you have any (e. g. in your hyprland config)**

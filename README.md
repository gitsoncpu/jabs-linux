# 2025 Setup



   
## ⚪ Marble Shell
##### https://github.com/imarkoff/Marble-shell-theme
   
```
git clone https://github.com/imarkoff/Marble-shell-theme.git
cd Marble-shell-theme
python install.py -ri -a --filled --launchpad -Pnp --opaque --hue 250 --sat 250
sudo python install.py --gdm --blue --filled --gdm-image /home/jason/Pictures/Wallpapers/space_blurp.png --gdm-blur=40 --gdm-darken=30
```

<img width="1535" height="864" alt="Screenshot From 2025-09-14 13-22-48" src="https://github.com/user-attachments/assets/5eab6f2a-0820-4390-95e2-288e155669bd" />
<img width="846" height="611" alt="Screenshot From 2025-09-14 13-24-21" src="https://github.com/user-attachments/assets/6080107d-52e0-4ab2-8476-d12f75cd83e1" />

## 🔌 Extensions

##### **User Themes** - https://extensions.gnome.org/extension/19/user-themes/

##### **Dash to Dock** - https://extensions.gnome.org/extension/307/dash-to-dock/

##### **Brightness Control Tray** - https://extensions.gnome.org/extension/2645/brightness-control-using-ddcutil/  ``` (GNOME 49 should have this) ``` 

##### **AppIndicator Support - tray icons** - https://extensions.gnome.org/extension/615/appindicator-support/ 

##### **Top Bar Organizer** - https://extensions.gnome.org/extension/4356/top-bar-organizer/


## 👾 Misc

##### Starship https://starship.rs/

##### Wofi Theme - https://github.com/quantumfate/wofi  
  
##### Browser Startpage/New Tab - https://gitlab.com/fazzi/startpage
  
##### Chromium browser emojis - https://aur.archlinux.org/packages/noto-color-emoji-fontconfig

##### /etc/passwd to change shell if password issue

#####  * IPV6 DHCP only

##### Remove firewall-applet in /usr/bin/firewall-applet

```
#applet = TrayApplet()
#applet.show()
sys.exit(app.exec())
```

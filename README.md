# 2025 GNOME



<img width="1535" height="864" alt="Screenshot From 2025-09-23 23-31-08" src="https://github.com/user-attachments/assets/0c190adf-0712-411c-858d-bb7e12bd8222" />

<img width="846" height="611" alt="Screenshot From 2025-09-23 23-31-50" src="https://github.com/user-attachments/assets/977137f0-d61c-405e-8dbf-69c6cff7bf55" />


### 🔌 Extensions
#### gnome-browser-connector + browser extension required
##### **User Themes** - https://extensions.gnome.org/extension/19/user-themes/

##### **Dash to Dock** - https://extensions.gnome.org/extension/307/dash-to-dock/

##### **Brightness Control Tray** - https://extensions.gnome.org/extension/2645/brightness-control-using-ddcutil/  ``` (GNOME 49 added) ``` 

##### **Status Icons** - https://extensions.gnome.org/extension/7332/status-icons/


### 👾 Misc

##### 🎨 Marble Shell https://github.com/imarkoff/Marble-shell-theme
 
```
git clone https://github.com/imarkoff/Marble-shell-theme.git
cd Marble-shell-theme
python install.py -ri -a --filled --launchpad -Pnp --opaque --hue 155 --sat 250
```
##### Firefox Theme https://addons.mozilla.org/en-US/firefox/addon/pixel-storm-in-green-and-pink/

##### Starship https://starship.rs/

##### Wofi Theme - https://github.com/quantumfate/wofi  
  
##### Browser Startpage/New Tab - https://gitlab.com/fazzi/startpage
  
##### Chromium browser emojis - https://aur.archlinux.org/packages/noto-color-emoji-fontconfig

##### /etc/passwd to change shell if password issue
 
#####  * IPV6 DHCP only for VPN leaks *

##### Remove firewall-applet in /usr/bin/firewall-applet

```
#applet = TrayApplet()
#applet.show()
sys.exit(app.exec())
```

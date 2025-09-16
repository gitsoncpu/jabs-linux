# 2025 GNOME



   
### 🎨 Marble Shell
##### https://github.com/imarkoff/Marble-shell-theme
##### set hue from 0 - 360    
```
git clone https://github.com/imarkoff/Marble-shell-theme.git
cd Marble-shell-theme
python install.py -ri -a --filled --launchpad -Pnp --opaque --hue 155 --sat 250
```
##### gdm edit
```
sudo python install.py --gdm --blue --filled --gdm-image PATHTOIMAGE --gdm-blur=40 --gdm-darken=30
```
<img width="1535" height="864" alt="489324111-8b49eafc-67eb-44aa-986e-d4cbdb46fd99(1)" src="https://github.com/user-attachments/assets/f6d9c15a-2788-461c-9bb9-4080553373c3" />

<img width="846" height="611" alt="Screenshot From 2025-09-14 14-32-32" src="https://github.com/user-attachments/assets/76210592-5e1f-4136-a2f4-beef15c20eb4" />


### 🔌 Extensions
#### gnome-browser-connector + browser extension required
##### **User Themes** - https://extensions.gnome.org/extension/19/user-themes/

##### **Dash to Dock** - https://extensions.gnome.org/extension/307/dash-to-dock/

##### **Brightness Control Tray** - https://extensions.gnome.org/extension/2645/brightness-control-using-ddcutil/  ``` (GNOME 49 added) ``` 

##### **Status Icons** - https://extensions.gnome.org/extension/7332/status-icons/


### 👾 Misc

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

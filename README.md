# 2025 Setup



   
## ⚪ Marble Shell
##### https://github.com/imarkoff/Marble-shell-theme
   
```
git clone https://github.com/imarkoff/Marble-shell-theme.git
cd Marble-shell-theme
python install.py -ri -a --filled --launchpad -Pnp --opaque --hue 250 --sat 250
sudo python install.py --gdm --blue --filled --gdm-image /home/jason/Pictures/Wallpapers/space_blurp.png --gdm-blur=40 --gdm-darken=30
```
<img width="1535" height="864" alt="Screenshot From 2025-09-14 11-15-49" src="https://github.com/user-attachments/assets/1dd1a0e4-6743-40d6-b5ce-e24bed87224a" />


## 🔌 Extensions

#### **User Themes** - https://extensions.gnome.org/extension/19/user-themes/

#### **Dash to Dock** - https://extensions.gnome.org/extension/307/dash-to-dock/

#### **Brightness Control Tray** - https://extensions.gnome.org/extension/2645/brightness-control-using-ddcutil/  ``` (GNOME 49 should have this) ``` 

#### **AppIndicator Support - tray icons** - https://extensions.gnome.org/extension/615/appindicator-support/ 

#### **Top Bar Organizer** - https://extensions.gnome.org/extension/4356/top-bar-organizer/


## 👾 Misc

#### Starship https://starship.rs/

#### Wofi Theme - https://github.com/quantumfate/wofi  
  
#### Browser Startpage/New Tab - https://gitlab.com/fazzi/startpage
  
#### Chromium browser emojis - https://aur.archlinux.org/packages/noto-color-emoji-fontconfig

#### /etc/passwd to change shell if password issue

####  * IPV6 DHCP only

#### Remove firewall-applet in /usr/bin/firewall-applet

```
#applet = TrayApplet()
#applet.show()
sys.exit(app.exec())
```

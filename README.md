# 2025 👹 My Linux stuff               

### 6/28 - 8/4
###### Void + XFCE, Sway, Hyprland

### 8/4 - 8/21
###### Cachy + Hyprperks DE

### 8/21 -
###### Endeavour + GNOME


   
## ⚪ Marble Shell
`https://github.com/imarkoff/Marble-shell-theme`
   
```
cd Marble-shell-theme
python install.py -ri -a --filled --launchpad -Pnp --opaque --hue 160
```
<img width="2560" height="1440" alt="Screenshot From 2025-08-23 20-00-39" src="https://github.com/user-attachments/assets/12c20366-d85e-4ae9-b6e2-4bfb3ff2b132" />



## 🔌 Extensions

#### **User Themes** 

> `https://extensions.gnome.org/extension/19/user-themes/`


#### **Top Bar Organizer** 

> `https://extensions.gnome.org/extension/4356/top-bar-organizer/`


#### **AppIndicator Support - tray icons** 

> `https://extensions.gnome.org/extension/615/appindicator-support/`


#### **Dash to Dock** 

> `https://extensions.gnome.org/extension/307/dash-to-dock/`


#### **Brightness Control Tray** 

> `https://extensions.gnome.org/extension/2645/brightness-control-using-ddcutil/`


## Misc, tweaks, fixes

* `https://github.com/quantumfate/wofi` - wofi theme

  
#### Chromium browser emojis 
```https://aur.archlinux.org/packages/noto-color-emoji-fontconfig```
####  * IPV6 DHCP only
#### Remove firewall-applet in /usr/bin/firewall-applet

```
#applet = TrayApplet()
#applet.show()
sys.exit(app.exec())
```

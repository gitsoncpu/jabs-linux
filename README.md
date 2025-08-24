# 2025 Linux stuff 👹              
#### 8/4 - 8/21
> Cachy + Hyprperks DE

#### 8/21 -
> Endeavour + GNOME


   
## Marble Shell
`https://github.com/imarkoff/Marble-shell-theme`
   
```
cd Marble-shell-theme
python install.py -ri -a --filled --launchpad -Pnp --opaque --hue 160
```

<img width="2560" height="1440" alt="Screenshot From 2025-08-23 18-59-06" src="https://github.com/user-attachments/assets/54322717-f2ec-49ac-aded-6e3b8eaec03b" />


## Extensions

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

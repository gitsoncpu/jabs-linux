# My GNOME 🐧

## Marble Shell
`https://github.com/imarkoff/Marble-shell-theme`

```
cd Marble-shell-theme
python install.py -ri -a --filled --launchpad -Pnp --opaque --hue 160
```
## Defaults
 * `https://github.com/quantumfate/wofi` - wofi theme
 * `https://github.com/romkatv/powerlevel10k` - zsh level up
 * $terminal = kgx
 * $browser = brave
 * IPV6 DHCP only


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



<img width="523" height="759" alt="untitled" src="https://github.com/user-attachments/assets/d0b1ceca-a714-4b8d-b153-c91c10734ef1" />



## Misc tweaks, fixes

#### Chromium browser emojis 
```https://aur.archlinux.org/packages/noto-color-emoji-fontconfig```

#### Remove firewall-applet in /usr/bin/firewall-applet

```
#applet = TrayApplet()
#applet.show()
sys.exit(app.exec())
```

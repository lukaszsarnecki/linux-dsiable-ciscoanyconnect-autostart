# How to disable autostart Cisco AnyConnect
### Go to: /etc/xdg/autostart/
```bash
cd /etc/xdg/autostart/
```
### Edit com.cisco.anyconnect.gui.desktop
```bash
sudo vi com.cisco.anyconnect.gui.desktop
```
### At the end of the file add
```bash
X-GNOME-Autostart-enabled=false
```
Restart computer

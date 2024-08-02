# info
startx11: Starts Termux X11 server and sets DISPLAY environment variable.
stopx11: Stops Termux X11 server and unsets DISPLAY environment variable.
stopvnc: Kills the VNC server on display :1.
restartvnc: Restarts the VNC server on display :1.
start-xfce4: Starts XFCE4 desktop environment.
start-box: Starts an Openbox session with additional components like XFCE panel, xcompmgr, PCManFM, wallpaper, and Cairo-Dock.
startvnc: Starts VNC server on display :1 with no localhost restriction.
# installation 
```sh
pkg update && pkg upgrade && pkg in wget && wget https://github.com/capt-dev/termux.x11-utils/releases/download/V1.0.0/x11-utils.deb && dpkg -i x11-utils.deb
```

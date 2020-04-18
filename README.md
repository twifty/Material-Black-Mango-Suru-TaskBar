KDE System Tray Icons
===

### Installation
Copy all icon files to `~/.local/share/plasma/desktoptheme/[theme name]/icons/`.

Delete your icon cache `rm ~/.cache/icon-cache.kcache`

If using `latte-dock`, restart it `killall latte-dock && latte-dock --cc &`, otherwise restart Plasma `killall plasmashell && kstart5 plasmashell &`.



### notes
If icons appear blurred, you need to contact the author of the relevant application and tell them to start using svg icons (We left the 90's decades ago!).

If an icon hasn't changed color, open a bug report. I'll see what I can do.

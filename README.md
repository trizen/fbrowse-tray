fbrowse-tray
============

A file-browser through a Gtk2 tray status icon.

![fbrowse-tray](https://3.bp.blogspot.com/-J3sjyKKTRQw/U3U3UpTBmZI/AAAAAAAAQ8g/yIJXgEYBa8U/s1600/2014-05-16-005138_1920x1080_scrot.png)

----

## USAGE

```
usage: fbrowse-tray [options] [dir]

options:
    -r            : order files before directories
    -d            : display only directories
    -T            : set the path of files as tooltips
    -e            : get the mimetype by extension only (faster)
    -i [name]     : name of the status icon (default: system-file-manager)
    -f [command]  : command to open the files with (default: pcmanfm)
    -t [command]  : terminal command for "Open in terminal" (default: xterm)
    -m [type]     : type of menu icons (default: menu)
                    more: dnd, dialog, button, small-toolbar, large-toolbar

example:
    fbrowse-tray -f thunar -t sakura -m dnd /my/dir
```

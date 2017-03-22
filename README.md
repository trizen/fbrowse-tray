fbrowse-tray
============

```
usage: fbrowse-tray [options] [dir]

options:
    -r            : order files before directories
    -d            : display only directories
    -T            : set the path of files as tooltip
    -e            : get the mimetype by extension only (faster)
    -i [name]     : change the status icon (default: file-manager)
    -f [command]  : command to open the files with (default: pcmanfm)
    -t [command]  : terminal command for "Open in terminal" (default: xterm)
    -m [size]     : size of the menu icons (default: menu)
                    more: dnd, dialog, button, small-toolbar, large-toolbar

example:
    fbrowse-tray -f thunar -t sakura -m dnd /my/dir
```

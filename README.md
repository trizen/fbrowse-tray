fbrowse-tray
============

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

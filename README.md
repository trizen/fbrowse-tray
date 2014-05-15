fbrowse-tray
============

A simple Gtk2 tray file-browser.

```
usage: fbrowse-tray [options] [dir]

options:
        -r            : order files before directories
        -t            : set the path of the file as tooltip
        -i [name]     : change the status icon (default: file-manager)
        -f [command]  : command to open the files with (default: pcmanfm)
        -m [size]     : size of the menu icons (default: menu)
                        more: dnd, dialog, button, small-toolbar, large-toolbar

example:
    fbrowse-tray -f thunar -m dnd /my/dir
```

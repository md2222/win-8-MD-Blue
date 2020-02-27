# win-8 MD Blue

GTK theme based on B00merang-Project Windows 8.1 theme that based on the Windows 8.1 appearance.

Modified for my taste.

Project in development. This is Beta version.

Taskbar modified for Cinnamon only. This is modified Linux Mint desktop.

![win-8-MD-Blue](https://raw.githubusercontent.com/md2222/win-8-MD-Blue/master/win-8-MD-Blue-example-01.png)

### Manual installation

Extract the zip file to the themes directory i.e. '/home/USERNAME/.themes'

Firefox get styles in \~/.config/gtk-3.0/gtk.css. 
If you put "scrollbar slider" style here, cinnamon think "Override the current theme's scrollbar width" enebled,
and set wrong value in \~/.gtkrc-2.0.<br>
If you disable the parameter, cinnamon delete "scrollbar slider" style from gtk.css. Sad.<br>
...<br>
You can override gtk theme used by Firefox: navigate to about:config create a string key widget.content.gtk-theme-override set the value to any theme name, for example "win-8 MD Blue". Restart Firefox to apply.



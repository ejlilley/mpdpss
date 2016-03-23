First make sure you have read [Requirements and Installation](Requirements_and_Installation.md).

Using dmenu or wimenu is a very fast way to switch playlists.

The first time you run mpdpss, it will prompt for a name to the current playlist. You should do the first run in a terminal or [using Zenity](Using_the_graphical_interface.md).

Then next time you run mpdpss, just choose which playlist to load, or press ESC to exit (which will just save the state of the current).

To use dmenu
```
$ mpdpss -d
```
To parse the options case insensitive (the default for mpdpss) and bottom to dmenu:
```
$ mpdpss -dm "-i -b"
```

![http://mpdpss.googlecode.com/files/mpdpss_dmenu.png](http://mpdpss.googlecode.com/files/mpdpss_dmenu.png)

To use wimenu
```
$ mpdpss -w
```
To parse a prompt with the word 'Choose' to wimenu:
```
$ mpdpss -wi "-p Choose"
```

![http://mpdpss.googlecode.com/files/mpdpss_wimenu.png](http://mpdpss.googlecode.com/files/mpdpss_wimenu.png)

######  ######
Please, see [Using the text interface](Using_the_text_interface.md) for all available commands for mpdpss. See also 'man dmenu' and 'man wimenu'.

If you always want to use the menu, or if you want to make any option the default, edit $HOME/.mpdpss.conf, which will be generated the first time you run mpdpss.
mpdpss will work in any UNIX-like system, including Linux, MAC OS X, Solaris and BSD, and in Windows using Cygwin.

[mpc (>= 0.19)](http://mpd.wikia.com/wiki/Client:Mpc) is required for the latest package. If you can't by some reason upgrade mpc, and mpdpss hasn't been able to save the states of playlists, ask me for the older mpdpss 1.5.

[Zenity (>= 2.14)](http://live.gnome.org/Zenity) is required if you want to use the GTK+ graphical interface. Zenity doesn't require you to install GNOME libraries. Versions older than 2.14 might bring errors that would make mpdpss stop.

[dmenu](http://tools.suckless.org/dmenu/) or [wmii (>= 3.9beta)](http://wmii.suckless.org/) is required if you want to switch using menus. dmenu is very small and packaged in some distributions as "dwm-tools", while wmii provides wimenu and is a full window manager.

If you use a Debian based system, you should prefer the .deb package. See [Debian based systems](#Debian_based_systems.md).

For any other Unix-like system: [All systems](#All_systems.md).

###  ###

---

###  ###
###  ###
### Debian based systems ###
To install MPD, mpc, Zenity (optional), and dmenu (optional), you can use your package manager or type the following in a terminal (never type the '$'):

```
$ sudo apt-get install mpd mpc zenity dwm-tools

# Type your password if needed
```
or
```
$ su -c 'apt-get install mpd mpc zenity dwm-tools'

# Type root password
```

Download the latest .deb package [available here](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=UHD9U4CGJ3MJ2). Depending on your system, you can just double click on it. Or you can install it in a terminal:

```
$ sudo dpkg -i mpdpss_1.8_all.deb

# Type your password if needed
```
or
```
$ su -c 'dpkg -i mpdpss_1.8_all.deb'

# Type root password
```

Now you can go ahead and check how to use the [text interface](Using_the_text_interface.md), the [graphical interface](Using_the_graphical_interface.md) or the [menu](Using_the_menu.md)!

###  ###

---

###  ###
###  ###
### All systems ###

The install script follows the [Filesystem Hierarchy Standard](http://en.wikipedia.org/wiki/Filesystem_Hierarchy_Standard). Should you have a look at the first lines of the install script to find out the possible paths where the files will be installed.

MPD, mpc, Zenity (optional), and dmenu (optional) should be available at your distribution repositories for simple installation. After making sure you have them installed, download the latest .tar.gz package [available here](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=UHD9U4CGJ3MJ2). Extract it using your favorite file manager or issuing the command (never type the '$'):

```
$ tar xvf mpdpss-1.8.tar.gz
```

Then go to the directory you extracted:

```
$ cd mpdpss-1.8
```

And run .install **AS ROOT**:

```
$ sudo ./install

# Type your password if needed
```
or
```
$ su -c './install'

# Type root password
```

If mpdpss doesn't work as expected, we could work together to fix that if you open an [issue](http://code.google.com/p/mpdpss/issues/list), or installing [bash](http://www.gnu.org/software/bash/) should solve most problems.

Now you can go ahead and check how to use the [text interface](Using_the_text_interface.md), the [graphical interface](Using_the_graphical_interface.md) or the [menu](Using_the_menu.md)!
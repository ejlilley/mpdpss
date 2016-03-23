**2010-02-21 - 1.8 release**  **-Important-**
  * mpdpss: added a workaround for a bug that could bring volume to 0.
  * mpdpss: adapted to use dmenu or wimenu.
  * dwm-tools added as a recommend (deb package).
  * mpdpss: added option -d, to choose playlists with dmenu.
  * mpdpss: added option -m, to parse options to dmenu.
  * mpdpss: added option -w, to choose playlists with wimenu.
  * mpdpss: added option -i, to parse options to wimenu.
  * mpdpss: bug that would make it remember last loaded playlist when no playlist was loaded, fixed in the GUI now aswell.
  * install: fixed some issues.

**2010-02-18 - 1.7.3 release**
  * mpdpss: modified zenity arguments parsing.
  * revised dependencies versions.

**2010-02-17 - 1.7.2 release**
  * mpdpss: better locale detection.
  * mpdpss: use of pidof command removed.
  * mpdpss: fixed a bug that would make it remember last loaded playlist when no playlist was loaded.
  * uninstall: fixed removing per user files.
  * other minor fixes.

**2010-02-09 - 1.7.1 release**
  * mpdpss.en: fixed broken translation file.

**2010-02-09 - 1.7 release**
  * added translation support.
  * included Portuguese translation.
  * added configuration file.
  * added install script.
  * included man page for all packages.
  * more bugs fixed.

**2010-02-05 - 1.6 release**
  * mpdpss: totally revised for more POSIX compliance.
  * mpdpss: added option -h, to display a brief help.
  * mpdpss: added option -n, for output with no colors.
  * mpdpss: added option -z, to just switch playlists without saving the state of the current.
  * fixed small window sizes.
  * added a logo for window decoration.
  * more bug fixes.

**2010-02-02 - 1.5.1 release**  **-Important-**
  * mpdpss: fixed a bug brought by upgrading mpc to version 0.19, which would cause it not to store the state of playlists.

**2010-01-31 - 1.5 release**
  * mpdpss: adapted to graphical interface support using zenity (option -g).
  * option -p added, which prompts for a name to save current playlist.
  * zenity added as a recommend.

**2010-01-20 - 1.0 release**
  * mpdpss: all rewritten from scratch.
  * genres tag are not needed anymore.
  * mpd configuration doesn't need to be in the $HOME anymore.
  * consume mode not needed anymore.
  * playlists not modified anymore.
  * no need to edit the script anymore.
  * states saved in a per user mpdpss\_state file now.
  * mpc added as a dependency.

**2010-01-08 - 0.1.2b release**
  * Fixed a bug where mpd.conf should include absolute paths, now the use of ~ is supported for home directory.

**2010-01-06 - 0.1.1b release**
  * Documentation modified.
  * Added beta state to the package.

**2010-01-05 - 0.1 release**
  * First release.
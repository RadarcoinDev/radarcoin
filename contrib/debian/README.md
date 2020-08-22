
Debian
====================
This directory contains files used to package radarcoind/radarcoin-qt
for Debian-based Linux systems. If you compile radarcoind/radarcoin-qt yourself, there are some useful files here.

## radarcoin: URI support ##


radarcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install radarcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your radarcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/radarcoin128.png` to `/usr/share/pixmaps`

radarcoin-qt.protocol (KDE)


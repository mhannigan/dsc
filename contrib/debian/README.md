
Debian
====================
This directory contains files used to package dscd/dsc-qt
for Debian-based Linux systems. If you compile dscd/dsc-qt yourself, there are some useful files here.

## dsc: URI support ##


dsc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dsc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dscqt binary to `/usr/bin`
and the `../../share/pixmaps/dsc128.png` to `/usr/share/pixmaps`

dsc-qt.protocol (KDE)



Debian
====================
This directory contains files used to package OZTGd/OZTG-qt
for Debian-based Linux systems. If you compile OZTGd/OZTG-qt yourself, there are some useful files here.

## pivx: URI support ##


OZTG-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install OZTG-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your OZTG-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

OZTG-qt.protocol (KDE)


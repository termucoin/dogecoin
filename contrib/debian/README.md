
Debian
====================
This directory contains files used to package nerocashd/nerocash-qt
for Debian-based Linux systems. If you compile nerocashd/nerocash-qt yourself, there are some useful files here.

## nerocash: URI support ##


nerocash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nerocash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nerocash-qt binary to `/usr/bin`
and the `../../share/pixmaps/nerocash128.png` to `/usr/share/pixmaps`

nerocash-qt.protocol (KDE)


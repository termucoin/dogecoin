
Debian
====================
This directory contains files used to package noncecashd/noncecash-qt
for Debian-based Linux systems. If you compile noncecashd/noncecash-qt yourself, there are some useful files here.

## noncecash: URI support ##


noncecash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install noncecash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your noncecash-qt binary to `/usr/bin`
and the `../../share/pixmaps/noncecash128.png` to `/usr/share/pixmaps`

noncecash-qt.protocol (KDE)


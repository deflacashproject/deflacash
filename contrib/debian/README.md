
Debian
====================
This directory contains files used to package deflacashd/deflacash-qt
for Debian-based Linux systems. If you compile deflacashd/deflacash-qt yourself, there are some useful files here.

## deflacash: URI support ##


deflacash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install deflacash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your deflacashqt binary to `/usr/bin`
and the `../../share/pixmaps/deflacash128.png` to `/usr/share/pixmaps`

deflacash-qt.protocol (KDE)


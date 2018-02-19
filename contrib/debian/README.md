
Debian
====================
This directory contains files used to package virtusd/virtus-qt
for Debian-based Linux systems. If you compile virtusd/virtus-qt yourself, there are some useful files here.

## virtus: URI support ##


virtus-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install virtus-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your virtus-qt binary to `/usr/bin`
and the `../../share/pixmaps/virtus128.png` to `/usr/share/pixmaps`

virtus-qt.protocol (KDE)


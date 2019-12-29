
Debian
====================
This directory contains files used to package litegenxd/litegenx-qt
for Debian-based Linux systems. If you compile litegenxd/litegenx-qt yourself, there are some useful files here.

## litegenx: URI support ##


litegenx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install litegenx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your litegenx-qt binary to `/usr/bin`
and the `../../share/pixmaps/litegenx128.png` to `/usr/share/pixmaps`

litegenx-qt.protocol (KDE)



Debian
====================
This directory contains files used to package lualad/luala-qt
for Debian-based Linux systems. If you compile lualad/luala-qt yourself, there are some useful files here.

## luala: URI support ##


luala-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install luala-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your luala-qt binary to `/usr/bin`
and the `../../share/pixmaps/luala128.png` to `/usr/share/pixmaps`

luala-qt.protocol (KDE)


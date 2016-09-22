
Debian
====================
This directory contains files used to package returnbitd/returnbit-qt
for Debian-based Linux systems. If you compile returnbitd/returnbit-qt yourself, there are some useful files here.

## returnbit: URI support ##


returnbit-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install returnbit-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your returnbit-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

returnbit-qt.protocol (KDE)


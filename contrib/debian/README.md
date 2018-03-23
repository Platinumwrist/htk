
Debian
====================
This directory contains files used to package htkd/htk-qt
for Debian-based Linux systems. If you compile htkd/htk-qt yourself, there are some useful files here.

## htk: URI support ##


htk-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install htk-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your htkqt binary to `/usr/bin`
and the `../../share/pixmaps/htk128.png` to `/usr/share/pixmaps`

htk-qt.protocol (KDE)



Debian
====================
This directory contains files used to package rupeesd/rupees-qt
for Debian-based Linux systems. If you compile rupeesd/rupees-qt yourself, there are some useful files here.

## rupees: URI support ##


rupees-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rupees-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rupeesqt binary to `/usr/bin`
and the `../../share/pixmaps/rupees128.png` to `/usr/share/pixmaps`

rupees-qt.protocol (KDE)


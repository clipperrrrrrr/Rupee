
Debian
====================
This directory contains files used to package digitalrupeed/digitalrupee-qt
for Debian-based Linux systems. If you compile digitalrupeed/digitalrupee-qt yourself, there are some useful files here.

## digitalrupee: URI support ##


digitalrupee-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install digitalrupee-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your digitalrupeeqt binary to `/usr/bin`
and the `../../share/pixmaps/digitalrupee128.png` to `/usr/share/pixmaps`

digitalrupee-qt.protocol (KDE)


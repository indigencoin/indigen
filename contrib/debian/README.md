
Debian
====================
This directory contains files used to package indigend/indigen-qt
for Debian-based Linux systems. If you compile indigend/indigen-qt yourself, there are some useful files here.

## indigen: URI support ##


indigen-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install indigen-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your indigenqt binary to `/usr/bin`
and the `../../share/pixmaps/indigen128.png` to `/usr/share/pixmaps`

indigen-qt.protocol (KDE)


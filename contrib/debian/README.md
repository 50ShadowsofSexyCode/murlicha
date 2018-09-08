
Debian
====================
This directory contains files used to package murlichad/murlicha-qt
for Debian-based Linux systems. If you compile murlichad/murlicha-qt yourself, there are some useful files here.

## murlicha: URI support ##


murlicha-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install murlicha-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your murlicha-qt binary to `/usr/bin`
and the `../../share/pixmaps/murlicha128.png` to `/usr/share/pixmaps`

murlicha-qt.protocol (KDE)


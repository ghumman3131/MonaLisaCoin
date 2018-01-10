
Debian
====================
This directory contains files used to package monalisacoind/monalisacoin-qt
for Debian-based Linux systems. If you compile monalisacoind/monalisacoin-qt yourself, there are some useful files here.

## monalisacoin: URI support ##


monalisacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install monalisacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your monalisacoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

monalisacoin-qt.protocol (KDE)


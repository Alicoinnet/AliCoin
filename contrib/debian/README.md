
Debian
====================
This directory contains files used to package alicoind/alicoin-qt
for Debian-based Linux systems. If you compile alicoind/alicoin-qt yourself, there are some useful files here.

## alicoin: URI support ##


alicoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install alicoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your alicoinqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

alicoin-qt.protocol (KDE)


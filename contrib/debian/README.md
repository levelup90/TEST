
Debian
====================
This directory contains files used to package timcoind/timcoin-qt
for Debian-based Linux systems. If you compile timcoind/timcoin-qt yourself, there are some useful files here.

## timcoin: URI support ##


timcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install timcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your timcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/timcoin128.png` to `/usr/share/pixmaps`

timcoin-qt.protocol (KDE)



Debian
====================
This directory contains files used to package crystalcoind/crystalcoin-qt
for Debian-based Linux systems. If you compile crystalcoind/crystalcoin-qt yourself, there are some useful files here.

## crystalcoin: URI support ##


crystalcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install crystalcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your crystalcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

crystalcoin-qt.protocol (KDE)


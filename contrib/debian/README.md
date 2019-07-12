
Debian
====================
This directory contains files used to package bochacoind/bochacoin-qt
for Debian-based Linux systems. If you compile bochacoind/bochacoin-qt yourself, there are some useful files here.

## bochacoin: URI support ##


bochacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bochacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bochacoinqt binary to `/usr/bin`
and the `../../share/pixmaps/bochacoin128.png` to `/usr/share/pixmaps`

bochacoin-qt.protocol (KDE)


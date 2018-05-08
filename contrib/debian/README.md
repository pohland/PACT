
Debian
====================
This directory contains files used to package PayPACTd/PayPACT-qt
for Debian-based Linux systems. If you compile PayPACTd/PayPACT-qt yourself, there are some useful files here.

## PayPACT: URI support ##


PayPACT-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install PayPACT-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your PayPACTqt binary to `/usr/bin`
and the `../../share/pixmaps/PayPACT128.png` to `/usr/share/pixmaps`

PayPACT-qt.protocol (KDE)


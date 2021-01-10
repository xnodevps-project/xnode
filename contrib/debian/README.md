
Debian
====================
This directory contains files used to package xnoded/xnode-qt
for Debian-based Linux systems. If you compile xnoded/xnode-qt yourself, there are some useful files here.

## xnode: URI support ##


xnode-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install xnode-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your xnode-qt binary to `/usr/bin`
and the `../../share/pixmaps/xnode128.png` to `/usr/share/pixmaps`

xnode-qt.protocol (KDE)


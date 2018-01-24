
Debian
====================
This directory contains files used to package fxcd/fxc-qt
for Debian-based Linux systems. If you compile fxcd/fxc-qt yourself, there are some useful files here.

## fxc: URI support ##


fxc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fxc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fxc-qt binary to `/usr/bin`
and the `../../share/pixmaps/fxc128.png` to `/usr/share/pixmaps`

fxc-qt.protocol (KDE)


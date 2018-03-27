
Debian
====================
This directory contains files used to package wantd/want-qt
for Debian-based Linux systems. If you compile wantd/want-qt yourself, there are some useful files here.

## want: URI support ##


want-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install want-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your want-qt binary to `/usr/bin`
and the `../../share/pixmaps/want128.png` to `/usr/share/pixmaps`

want-qt.protocol (KDE)


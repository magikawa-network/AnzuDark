
Debian
====================
This directory contains files used to package anzudarkd/anzudark-qt
for Debian-based Linux systems. If you compile anzudarkd/anzudark-qt yourself, there are some useful files here.

## anzudark: URI support ##


anzudark-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install anzudark-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your anzudarkqt binary to `/usr/bin`
and the `../../share/pixmaps/anzudark128.png` to `/usr/share/pixmaps`

anzudark-qt.protocol (KDE)


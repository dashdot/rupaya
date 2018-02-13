
Debian
====================
This directory contains files used to package rupayad/rupaya-qt
for Debian-based Linux systems. If you compile rupayad/rupaya-qt yourself, there are some useful files here.

## rupaya: URI support ##


rupaya-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rupaya-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rupayaqt binary to `/usr/bin`
and the `../../share/pixmaps/rupaya128.png` to `/usr/share/pixmaps`

rupaya-qt.protocol (KDE)


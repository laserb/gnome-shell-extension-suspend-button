gnome-shell-extension-suspend-button
====================================

GNOME Shell Extension Suspend-Button for GNOME 3.34

For older versions of gnome-shell use the release/3.2x branch.


Installation
============

Run

```
make
make install
```

This will build and install the extension to ``~/.local/share/gnome-shell/extensions/``.   

Alternatively run
```
make
DESTDIR=/ make install
```

This will build and install the extension to ``$(DESTDIR)/usr/share/gnome-shell/extensions/``.

yabr: Yet Another (Desktop) Background Randomiser
=================================================

Change the desktop background to a random image (from paths you specify) when you log in. Works on Gtk-3-based Linux desktops (Gnome Shell, Cinnamon, Unity, ...) and Windows XP to 7.

Originally written to teach myself Qt back when Windows didn't have this sort of thing built in; now mostly redundant, but I still use it.


Build
-----

Should work with Qt 4 or 5:

    qmake
    make

Binaries are placed in `bin`.


Run
---

Run `yabr-config` first to set everything up. You can then change the background manually through the configuration program, or by running `yabr`. Check the box in the configuration program to make it change the background automatically at startup.


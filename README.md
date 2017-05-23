Clone of iBus-Unikey for fixing some crash.

== Todo list: ==
1. Refactoring to gain some inside or at least familiar with ibus-unikey code base.
2. Convert from autotool to cmake.
3. Update with upstream unikey engine.
4. Add automated test. But how do we known if this project is done/ornot. Any Telex / VNI specification for reference?
5. Now, if ever we reach to this point, then what?

Original/Official Unikey engine website, mainternanced by its great/generous author (Pham Kim Long): http://www.unikey.org/

== How to build ==

=== Original ibus-unikey (on Ubuntu 16.04) ===

sudo apt install libgconf-2-4

sudo apt install autopoint

sudo apt install autoconf

sudo apt install intltool

sudo apt install libtool

sudo apt install libibus-1.0-dev

sudo apt install python

sudo apt search gtk+

sudo apt search gtk

sudo apt search "gtk+"

sudo apt search "gtk+" | grep "gtk+"

sudo apt search libgtk

sudo apt install libgtk2mm

sudo apt search  libgtkmm

sudo apt install libgtkmm-2.4-dev

Overview of Imput Method for CJK (and Vietnamese)

https://blogs.gnome.org/happyaron/2011/01/15/linux-input-method-brief-summary/

User BongNV on github already did this more than a year ago: https://github.com/bongnv/ibus-unikey

And his own introduction: http://bongnv.github.io/2016/03/another-ibus-unikey.html

And another unikey-based engine:

https://devhub.io/repos/wilonth-BoGoEngine

It's much fun now, or a big mess to sort out.

-----------------------------------------------------------------------
Original readme

IBus-Unikey IME
---------------
Copyright (C) 2009 - 2012 Ubuntu-VN <http://www.ubuntu-vn.org>
Author: Lê Quốc Tuấn <mr.lequoctuan@gmail.com>
Home: http://ibus-unikey.googlecode.com
License: GNU GENERAL PUBLIC LICENSE v3
---------------------------------------------
ibus-unikey is an ibus input method engine.
It use ukengine for progress key event.
(a modified version of ukengine)

For support: goto http://forum.ubuntu-vn.org/viewforum.php?f=85

Please read INSTALL for how to install


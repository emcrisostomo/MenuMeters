MenuMeters
==========

`MenuMeters` is a set of CPU, memory, disk, and network monitoring tools for
macOS.  [Originally][original] created by Alex Harper, development stopped in
2015 and `MenuMeters` stopped working on OS X El Capitan.  my fork of
`MenuMeters` for El Capitan.

A [fork] was created on GitHub and the compatibility issues with OS X were
fixed.  The fork is being actively maintained.

I created this fork because I felt the need of streamlining the build and
release process.  I added a `Makefile` which builds `MenuMeters` from scratch,
and creates a DMG archive containing a PKG installer.

Building
--------

`MenuMeters` can be built from sources using the following command:

````
$ make
````

Installing
----------

`MenuMeters` can be installed downloading the DMG archive of the [latest
release][latest].  If you prefer to build the installer from source, just follow
the instructions in [Build](#build).

[original]: http://www.ragingmenace.com/software/menumeters/
[fork]: https://github.com/yujitach/MenuMeters
[latest]: https://github.com/emcrisostomo/MenuMeters/releases/latest

cmst
====

QT GUI for Connman with system tray icon.

The program provides graphical user interface to control the connman daemon.  The connman daemon
must be started as you normally would, this program just interfaces with that daemon. You can see
what technologies and services connman has found, and for wifi services an agent is registered to
assist in obtaining the information from you necessary to logon the wifi service.

The program requires that connman be installed and running.  The program depends on QT5, but only the base package. 

The [Wiki](https://github.com/andrew-bibb/cmst/wiki) has been started and announcements, news and other information can be found there.

[Screen shots:](https://github.com/andrew-bibb/cmst/wiki/3.-Screenshots) are now included in the Wiki

There is a PKGBUILD for this project in the Arch Linux AUR.

If you are not on Arch download the release and extract the files.  Then run:

    qmake
    make
    make install (as root)


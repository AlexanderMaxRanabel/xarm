# Xarm Server
--------

Xarm is a continuation of X Windows System and X11.
# Why Xarm is Started?

Xarm is started because X11 development is started to die. Xarm tries to modernize X11 and refactor some of the code so it can be easier to maintain.

# Why Not Wayland?

1. Wayland is a pretty new technology. While Wayland is started to became a more mature piece of software, some of the old X11 Software are vey bad at
working with Wayland. 
2. Wayland is getting the features X11 has over years.

## ORİGİNAL X11 README.MD

The Xarm server accepts requests from client applications to create windows,
which are (normally rectangular) "virtual screens" that the client program
can draw into.

Windows are then composed on the actual screen by the X server
(or by a separate composite manager) as directed by the window manager,
which usually communicates with the user via graphical controls such as buttons
and draggable titlebars and borders.

For a comprehensive overview of X Server and X Window System, consult the
following article:
https://en.wikipedia.org/wiki/X_server

All questions regarding this software should be directed at the
Xorg mailing list:

  https://lists.freedesktop.org/mailman/listinfo/xorg

The primary development code repository can be found at:

  https://gitlab.freedesktop.org/xorg/xserver

For patch submission instructions, see:

  https://www.x.org/wiki/Development/Documentation/SubmittingPatches

As with other projects hosted on freedesktop.org, X.Org follows its
Code of Conduct, based on the Contributor Covenant. Please conduct
yourself in a respectful and civilized manner when using the above
mailing lists, bug trackers, etc:

  https://www.freedesktop.org/wiki/CodeOfConduct

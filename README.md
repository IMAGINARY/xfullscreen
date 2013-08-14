xfullscreen
===========

Maximize the initially opened window of a program to completely fill
the available space on an X11 screen (aka fullscreen). 

Very useful if you want to build Linux based kiosk like systems that
don't have a window manager - just plain X11. It also allows to open
Firefox in fullscreen (this is what xfullscreen was initially made
for).

Usage:
  `xfullscreen COMMAND [ARGS]`

xfullscreen launches COMMAND and waits until it opens an X11 window.
This window is then resized to the dimensions of the X11 screen it
is on. This is based on xdotool.

Example:
  `xfullscreen firefox http://www.example.com`


# slock - simple screen locker

simple screen locker utility for X.
Compiled using Void Linux

# Requirements
In order to build slock you need the Xlib header files.
You will also need imlib2-devel

# Installation
Edit config.mk to match your local setup (slock is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install slock
(if necessary as root):

    make clean install


# Running slock
Simply invoke the 'slock' command. To get out of it, enter your password.
If using elh-dwm, you can use Super + X to lock your screen

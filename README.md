# Intro
This repository guide you to set the VNC environment.

# xubuntu
If you are using xubuntu, run the following command first:
$ sudo apt-get install vnc4server

we don't recommend tightvncserver
$ sudo apt-get install xubuntu-desktop xfce4 xfce4-goodies

then copy the content of 'xubuntu' to your xstartup file: ~/.vnc/xstartup

# gnome
If you are using gnome, things are different. Suppose your system is using gnome as the default desktop, then you don't have to install gnome-desktop. Run the command:

$ sudo apt-get install ubuntu-desktop gnome-panel gnome-settins-daemon metacity nautilus gnome-terminal

then copy the content of 'gnome' to your xstartup file: ~/.vnc/xstartup

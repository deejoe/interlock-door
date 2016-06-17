
Go to 

[http://deejoe.sdf.org/interlock](http://deejoe.sdf.org/interlock)

right click on door.asc and Save as ... or otherwise download the file
door.asc and save it to your computer.

Or, open a terminal emulator on a desktop or laptop GNU/Linux system (xterm gnome-terminal rxvt or
whatever), or on Mac (Terminal), and issue:

```
wget http://deejoe.sdf.org/interlock/door.asc
```

or

```
curl -O http://deejoe.sdf.org/interlock/door.asc
```

In all cases, navigate in a terminal emulator to where your copy of door.asc
has been saved, and then issue:

```
gpg -d door.asc
```

This will prompt you for a password and, once the password has been entered,
should display to you the file contents.


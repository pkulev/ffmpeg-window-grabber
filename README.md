Grab any X11 window with `ffmpeg`.

Usage
-----

    ./windowgrab.sh

Then click the window to grab it! You will have 2 seconds to remove mouse pointer so it will not be grabbed.
Press ^C to stop grabbing. Moving window around will break the recording.
After you have finished, file `grab-03-13-2017-11:34:01.mp4` will apper in current directory.

*Gentoo users!* `ffmpeg` should be compiled with **xcb** flag.

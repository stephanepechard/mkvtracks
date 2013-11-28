mkvtracks
=========

This is a simple script that launch a GUI to edit a mkv file tracks.
At the moment, you can only remove some tracks and generate a new mkv.
Tested successfully on Linux.

Dependencies
------------
To make `mkvtracks` run, you'll need:

- [wxPython](http://www.wxpython.org/) for the GUI ;
- [mkvtoolnix](http://www.bunkus.org/videotools/mkvtoolnix/) to handle mkv files.

They are directly available in any good Linux distribution. A simple:

    sudo aptitude install python-wxgtk2.8 mkvtoolnix

should give them to you if you don't have them already.

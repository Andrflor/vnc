vnc
===

VNC server application for iOS Simulators running on mac machines. This repo is a fork of [OSXvnc](http://sourceforge.net/projects/osxvnc) with additions from [SharedAppVNC](http://sourceforge.net/projects/shared-app-vnc).


Requirements
------------

* XCode

User Quick Start
----------------

To only show the particular window via VNC on OS X, try the following commandline example:
```
OSXvnc-server -rfbnoauth -sharedwinname "*irefo*"
```

This will look for a window owned by a process with the name *irefo* (* = wildcard) and only show that window during the VNC session.


Contributing
------------
Fork the project, make a change, and send a pull request!

License
------------
See the LICENSE file

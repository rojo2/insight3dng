# Insight3D NG, Versión 0.3.3

## Compiling under Linux

To compile `insight3d` under Linux, you must have the following libraries: 

	- opencv
	- opengl
	- SDL
	- libxml2 (to parse xml files)
	- lapack 
    - blas (min. 1.2-8 (Debian/Ubuntu))
	- libgtk+-2.0

And this should be pretty much everything. Also, pkg-config should know about 
those libraries.

Makefile and source code is in the "insight3d" subdirectory. There's no 
configuration, just execute "make" in the "insight3d" subdirectory. 

## Compiling on Windows

You'll need the same libraries. You'll need to setup the paths to include 
and bin directories of these libraries in Visual Studio. The project has been
compiled using Microsoft Visual C++ Express 2008.

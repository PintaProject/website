# Building Pinta

## Building Pinta on Linux

On Linux you can build Pinta on two ways: Either you can build by opening Pinta.sln in MonoDevelop and building from there, or you can use the makefile. When using the makefile you can install Pinta directly in to the default directory or specify a directory.

### Building with the makefile

Building Pinta requires the following software:

`mono mono-xbuild automake autoconf libmono-cairo2.0-cil gtk-sharp2`

Pinta only supports version 2.8 or higher of Mono.

To build Pinta, run:

`./autogen.sh`

`make`

`sudo make install`

or if building from a tarball, run:

`./configure`

`make`

`sudo make install`

To use different installation directory than the default (/usr), run this instead:

`./autogen.sh --prefix=<install directory>`

To uninstall Pinta, run:

`sudo make uninstall`

To clean all files created during the build process, run:

`make cleanall`

Note This will require you to rerun autogen.sh in order to run more make commands.

For a list of more make commands, run:

`make help`

## Building Pinta on Windows & Mac

On Windows and Mac, you open Pinta.sln with Monodevelop, SharpDevelop or Visual Studio and build from there. To build the Windows installer you can use Visual Studio with the Votive plugin to build the WiX project.

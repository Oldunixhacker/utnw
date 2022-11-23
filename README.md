# UTNW: Unix Tools for Native Windows

A collection of several Linux utilities compiled with `mingw-w32` for native Windows
support. The simple Inno Setup-based installer should add a bit of Unix to your Windows
system.

Examples include:

* `sed`: Advanced text editor from several sets of Linux userlands
* `nano`: Basic, free Pico-like text editor from the GNU userland
* `bash`: GNU Bourne-Again Shell. You can also run `sh` to start bash, because `sh`
  in UTNW is basically just a link to `bash`.
* More: try `ls C:\UTNW\bin` for a list

## Developers: Add your own programs

You can compile your own Linux programs with `mingw-w32` and add them here by making
a pull request. It will be accepted if it's useful enough.

If it's someone else's program, follow the program's license.

You can also install the program to `C:\UTNW\bin`, the home of Unix utilities installed
to your system.

## Support

UTNW is tested on Windows 11. It should also work on Windows 10, 8.1, and ReactOS, though
it should be tested yourself.

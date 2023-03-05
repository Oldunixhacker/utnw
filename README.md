# WARNING!

UTNW is sometimes identified as a trojan by some anti-virus programs. This is not
correct. It is recommended to disable your anti-virus program before installing
UTNW.

# UTNW: Unix Tools for Native Windows

A collection of several Linux utilities compiled with `mingw-w32` for native Windows
support.

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

You can also install the program to `C:\UTNW\bin`, the directory containing Unix utilities installed
on your system.

## Support

UTNW is tested on Windows 11. It should also work on Windows 10, though
it should be tested yourself.

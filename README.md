# amp-grib

This is a fork of the zyGrib project from http://www.zygrib.org/

Addt'l docs: https://maringret.wordpress.com/articles/ar_zygrib/

Homepage: https://github.com/arskom/amp-grib

## Compilation

On gentoo, do the following to install dependencies:

	emerge qwt qtcreator libnova

Other distros should install development packages in addition to the binaries

Use the .pro file in the src directory. The Makefile at the root of the
repository is there only for historical purposes and will be deleted.

Tested with Qt 5.9 using both GCC 6.4.0 and CLANG 5.0.1 on Linux only so far.

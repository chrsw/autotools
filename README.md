# autotools 

Examples of using Autotools family of tools: automake, autoconf, make, libtool, etc.

https://thoughtbot.com/blog/the-magic-behind-configure-make-make-install


Run:
$ aclocal   # generate an autotools m4 environment

$ autoconf  # generate configure from configure.ac

$ automake --add-missing # generate a Makefile from Makefile.am

Now the directory contains all the files needed for the user to run
$ ./configure && make && make install
- or -
$ ./configure
$ make
$ sudo make install

To build a distribution package, the Makefile has a target for that:
$ ./configure
$ make dist

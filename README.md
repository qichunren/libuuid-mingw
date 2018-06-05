# libuuid compatible MinGW

Forked from http://sourceforge.net/p/libuuidmingw/


## Build

    autoconf && aclocal && autoreconf && automake
    ./configure --host=i686-w64-mingw32 --prefix=/mingw32
    mingw32-make.exe
    mingw32-make.exe install

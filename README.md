### mingw-ldd

Tool to list dependencies of a dll using python and winedump.

Kudos to yan12125 for the original script:
https://gist.github.com/yan12125/63c7241596e628553d21

You can also checkout another similar tool:
https://github.com/LRN/ntldd

## Usage

    $ python dependency.py /usr/i686-w64-mingw32/bin/libpng16-16.dll
    Arch = i386
    Using default prefix /usr/i686-w64-mingw32/bin
    /usr/i686-w64-mingw32/bin/libgcc_s_sjlj-1.dll
    /usr/i686-w64-mingw32/bin/libwinpthread-1.dll
    /usr/i686-w64-mingw32/bin/zlib1.dll
    The following dependencies were not found:
    KERNEL32.dll
    msvcrt.dll
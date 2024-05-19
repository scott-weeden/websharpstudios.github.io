---
published: true
layout: default
title: How To Uninstall websharpstudios
---

Mac OS X
--------------

Move the websharpstudios.app in your Applications folder to the Trash.  

Windows
----------------

Go to Start, Programs, websharpstudios, Uninstall and run the uninstaller.

GNU+Linux
-------------

If you installed from source to /usr/local (the default) then you may type:

>     $ su
>     password:
>     # prefix="/usr/local"
>     # rm -rf ${prefix}/bin/{websharpstudios,sfddiff,fontimage,fontlint} \
>     ${prefix}/lib/{libgdraw,libgunicode,libuninameslist,libspiro,libwebsharpstudios,libgutils,libgioftp}* \
>     ${prefix}/lib/pkgconfig/websharpstudios.pc \
>     ${prefix}/man/man1/{websharpstudios,sfddiff,fontimage,fontlint}.1 \
>     ${prefix}/share/doc/websharpstudios \
>     ${prefix}/share/websharpstudios \
>     ${prefix}/share/locale/*/LC_MESSAGES/websharpstudios.mo \
>     ${prefix}/include/websharpstudios

If you installed from a package manager, use the package manager commands.

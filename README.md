# gettext-dev-windows
GNU gettext precompiled development files for windows

contents:
```
bin/
- gettext.exe, gettext.sh, xgettext.exe, ngettext.exe, ...
- msgattrib.exe, msgcat.exe, msgcomm.exe, msgconv.exe, ...
- intl-8.dll, gettextpo-0.dll, textstyle-0.dll, asprintf-0.dll, ...
include/
- textstyle/...
- libintl.h
- autosprintf.h
- gettext-po.h
- textstyle.h
lib/
- intl.lib, asprintf.lib, textstyle.lib, ... (static libraries)
- intl.dll.lib, asprintf.dll.lib, textstyle.dll.lib, ... (import library for dlls)
share/
- ...
```

These files are compiled with msys2 and Visual Studio 2019.

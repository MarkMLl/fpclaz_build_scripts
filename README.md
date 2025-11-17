# fpclaz_build_scripts
Scripts found useful when building the Free Pascal Compiler (FPC) etc.

fpc-filter-vt was written when attempting to work out the dependencies in FPC's text-mode IDE, it is tested on Linux and SunOS/Solaris.

Run it like

```
make GDB_V603=1 PP=ppcsparc-2.6.2 OPT='-O- -gl -Xs- -vt' all | fpc-filter-vt
```
HINT: If attempting recompilation of v3.2.2 with itself fails, look for REQUIREDVERSION2 in the Makefile and change it from 3.2.0 to 3.2.2.

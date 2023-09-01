# fpclaz_build_scripts
Scripts found useful when building the Free Pascal Compiler (FPC) etc.

fpc-filter-vt was written when attempting to work out the dependencies in FPC's text-mode IDE, it is tested on Linux and SunOS/Solaris.

Run it like

```
make GDB_V603=1 PP=ppcsparc-2.6.2 OPT='-O- -gl -Xs- -vt' all | fpc-filter-vt
```

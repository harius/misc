In April 2013, I started working on a small lisp implementation,
but I abandoned it almost immediately.

In June 2021, I started writing a new lisp from scratch.
The most basic stuff is implemented: functions, macros,
quasiquotes, etc. Dynamically loading shared libraries and
calling functions from them is also possible.

To build and run the REPL:
```
cmake -S . -B build
cmake --build build
build/zlisp-cli-bootstrap/zlisp-run module/cli/main.lisp
```

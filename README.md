Patched PyQt
============

This is a dump of the PyQt4 source code + patches to build debug libraries linked to the standard python27.dll but still to the debug Qt libraries

It requires a corresponding patched version of sip (https://github.com/martyngigg/sip-msvc) that includes a `wrappython.h` header
to be used in place of `Python.h`

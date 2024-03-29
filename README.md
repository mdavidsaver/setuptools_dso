# setuptools extension for building non-Python Dynamic Shared Objects

Building non-python shared libraries (eg. `libY.so`, `libY.dylib`, or `Y.dll`) for inclusion in a Python Wheel.

This extension is an alternative to bundling externally built
libraries in Python Wheel packages by providing the means to
replace an external build system (eg. Makefile) so that non-python
libraries to be built from source within the python ecosystem.

- Documentation at https://mdavidsaver.github.io/setuptools_dso
- Github project https://github.com/mdavidsaver/setuptools_dso
- PYPI https://pypi.org/project/setuptools-dso/

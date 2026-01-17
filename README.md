# build-info-cpp
Utility to inject build metadata to C++ builds.

It is a header-only library that provides information of the following metdata for C++ projects:
- compiler info
- version numbers
- build timestamps
- CUDA support

It relies on CMake to inject the metadata to the binaries.
It can be used for executables, shared, and static libraries.


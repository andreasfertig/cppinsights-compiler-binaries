# C++ Insights Compiler Binaries

This repository holds the macOS and Windows binaries for LLVM and Clang with all libraries enabled required to build C++ Insights.

## Windows

The Windows binaries lack compiler-rt and libClang. Hence I use my own builds for Windows.


## macOS

For LLVM, 6 to 8 macOS binaries have been distributed via the official LLVM release page (http://releases.llvm.org/download.html#git). However, nine seems to be delayed, with no indication whether it is ever coming. Starting with macOS 9, these are custom builds of my own. However, with Clang 14, I switched back to the binaries LLVM provides.


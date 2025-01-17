# TemplateRepository
This repository contains template for a project in C amd C++ language

## Installing catch2 in msys2
```
pkg-config -S mingw-w64-x86_64-catch
```
OR <br>
```
pkg-config -S mingw-w64-clang-x86_64-catch
```

## Building Static library
For debug mode
```
make -s lib-static-debug WALL=1 -j
```
For release mode
```
make -s lib-static-release WALL=1 -j
```
## Building Dynamic library
For debug
```
make -s ilb-dynamic-deubg WALL=1 -j
```
For release mode
```
make -s lib-static-release WALL=1 -j
```
## Building Executable
For debug
```
make -s build-debug WALL=1 -j
```
For release
```
make -s build-release WALL=1 -j6
```
## Cleaning
```
make -s clean -j
```

# AirCanvas

Draw in the air using your webcam. Built in C++ with OpenCV.

## Build (Windows)

Requires CMake, Visual Studio Build Tools (C++), and vcpkg.

```
cmake -S . -B build -DCMAKE_TOOLCHAIN_FILE=<path-to-vcpkg>/scripts/buildsystems/vcpkg.cmake
cmake --build build
.\build\Debug\AirCanvas.exe
```

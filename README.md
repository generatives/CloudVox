This repo is based on the Learn WebGPU web book and the below README is left over from that repo. Over time my intention is to turn it into a bloxel engine as a "learn C++" project. I will re-write the README as the project comes into shape.


LearnWebGPU - Code
==================

This repository contains the reference code base accompanying the [Learn WebGPU](learnwgpu.com) web book.

Branch `step080`: This corresponds to the code at the end of the page [Refactoring](http://localhost:8000/basic-3d-rendering/some-interaction/refactoring.html).

Building
--------

```
cmake . -B build
cmake --build build
```

Then run either `./build/App` (linux/macOS/MinGW) or `build\Debug\App.exe` (MSVC).

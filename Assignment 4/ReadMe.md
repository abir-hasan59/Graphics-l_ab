# OpenGL Triangle Project

## Author
**Name:** Md. Abir Hasan  
**ID:** 0432310005101059  

## Description
This project demonstrates a simple OpenGL program using **GLFW** and **GLAD** to render a triangle.  
The triangle color can be dynamically updated using shaders:
- **Default Mode:** The red color component of the triangle pulses smoothly over time.
- **Red Mode (Press R):** The triangle becomes solid red.
- **Exit (Press ESC):** Closes the application.

## Requirements
- OpenGL 3.3+
- GLFW
- GLAD
- C++ Compiler (g++/clang++/MSVC)

## Build Instructions
```bash
g++ main.cpp -lglfw -ldl -lGL -o triangle
./triangle

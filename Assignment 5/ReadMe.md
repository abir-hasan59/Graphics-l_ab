# OpenGL House Drawing Project

## Author
**Name:** Md Abir Hasan  
**ID:** 0432310005101059  

---

## 📌 Project Description
This project is a simple OpenGL program written in C++ using **GLFW** and **GLAD**.  
It draws a basic **house shape** consisting of:
- A triangle (roof)
- A square (body)

The project demonstrates the use of **vertex and fragment shaders**, VAOs, VBOs, and uniform color updates.

---

## 🛠️ Features
- Renders a **triangle** and **square** to form a house-like structure.  
- Uses **GLSL shaders** (vertex + fragment).  
- Dynamic **uniform color control** for the house.  
- Adjustable **viewport resize callback**.  
- Press **`9` key** to close the window.  

---

## 🚀 Requirements
- C++ Compiler (g++, MSVC, etc.)  
- [GLFW](https://www.glfw.org/)  
- [GLAD](https://glad.dav1d.de/)  
- OpenGL 3.3 or higher  

---

## ▶️ How to Run
1. Install **GLFW** and **GLAD**.  
2. Compile the code:  
   ```bash
   g++ main.cpp -lglfw -ldl -lGL -o house

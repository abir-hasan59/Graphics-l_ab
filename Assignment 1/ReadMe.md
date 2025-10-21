# OpenGL Window Initialization with Cyan Background

### 🧑‍💻 Author:
**Md. Abir Hasan**  
**ID: 0432310005101059**

---

## 📌 Project Description

This is a simple OpenGL program written in C++ that:

- Initializes a window using **GLFW**
- Loads OpenGL functions using **GLAD**
- Sets up a render loop
- Displays a **cyan-colored** background
- Closes the window when the **`A` key** is pressed

---

## 💻 Requirements

- C++ Compiler (g++, clang++, MSVC)
- GLFW
- GLAD
- OpenGL 3.3 or higher

---

## 🧩 How It Works

1. **GLFW** is used to create the window and handle input.
2. **GLAD** is used to load OpenGL function pointers.
3. The window background is set to **cyan** using:
   ```cpp
   glClearColor(0.0f, 1.0f, 1.0f, 1.0f);
   glClear(GL_COLOR_BUFFER_BIT);


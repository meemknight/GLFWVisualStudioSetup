# Plug And Play GLFW VisualStudio setup

---

## What is it?

---

I already configured a Visual Studio solution with everything that you need to start learning OpenGL!
I even added GLM, Imgui with extensions, and stb_image for you!

![image](https://github.com/user-attachments/assets/4832ff41-28b3-4e4e-a3e2-8ea5b27566e2)


---

## How to use?

If you just want to learn OpenGL from the https://learnopengl.com/ you can just delete the content from main.cpp and start from scratch!
*BUT* re-add ```#include <openglErrorReporting.h>``` and the ```enableReportGlErrors();``` line after you enable opengl!!!!!!!!
(it might not work on apple)

They are very important because they will enable OpenGL error reporting for you!!!!!!!!! And trust me you want that!

Other than that this is a normal visual studio solution, enjoy!

If you want other templates that use CMake, check out this video:
https://www.youtube.com/watch?v=FrVABOhRyQg

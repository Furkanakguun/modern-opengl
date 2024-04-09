
Modern OpenGL techniques
Create Windows and handle output
Vertex, Fragment and Geometry Shader
Draw 3D models
Use GLM(OpenGL Maths library)
Translate, rotate and scale models
User of interpolation
DIfferent types of Projection
Camera control and movement
Texture mapping
Phong Lighting Model
Directional, Point and Spot Lights
Importing pre-made models
Shadow Mapping
Implement a Skybox

In the realm of OpenGL development, the popularity of libraries can be gauged by how well they support developers in creating graphics applications, 
managing OpenGL context, handling user input, and interfacing with different hardware and operating systems. 
Some libraries are designed to complement OpenGL by providing higher-level functionalities,
while others are essential for the basic operation of any OpenGL application.

![image](https://github.com/Furkanakguun/modern_opengl/assets/45063194/855f218f-1663-4a07-ab44-9b5adc24863b)

1. GLFW
Purpose: Primarily used for creating windows, handling user input, and managing OpenGL contexts.
Popularity Reason: GLFW is lightweight, easy to use, and provides straightforward functionality for the specific task of window and input management. It's a go-to choice for both beginners and advanced users for creating OpenGL applications.
2. GLEW (OpenGL Extension Wrangler Library)
Purpose: Facilitates the use of OpenGL extensions by providing efficient run-time mechanisms to query the supported extensions on the target platform.
Popularity Reason: Almost indispensable for modern OpenGL development, GLEW allows developers to utilize the most advanced features of OpenGL without worrying about platform-specific limitations.
3. GLM (OpenGL Mathematics)
Purpose: A mathematics library designed for graphics software based on the syntax of GLSL (OpenGL Shading Language).
Popularity Reason: GLM is widely used for its comprehensive support for vector and matrix operations, transformations, and other mathematical functions critical for 3D graphics. It's designed specifically for OpenGL and mimics GLSL, making it intuitive for graphics developers.
4. Assimp (Open Asset Import Library)
Purpose: Provides a unified interface for importing many well-known 3D model formats into applications.
Popularity Reason: Assimp is popular because it simplifies the process of loading 3D models into OpenGL applications, supporting a wide range of file formats. It handles the tedious task of parsing and loading model data, allowing developers to focus on rendering and application logic.
5. Dear ImGui
Purpose: An immediate mode GUI (Graphical User Interface) library for creating dynamic tools and interfaces within OpenGL applications.
Popularity Reason: Its simplicity and ease of integration make Dear ImGui extremely popular for developing in-app GUIs. It's particularly favored for creating debug tools, editors, and prototypes within games and other graphics-intensive applications.
6. SOIL (Simple OpenGL Image Library)
Purpose: A tiny library used for loading textures from various image formats directly into OpenGL.
Popularity Reason: Though there are newer alternatives, SOIL remains popular for its simplicity and ease of use in loading images as textures in OpenGL applications without needing to write complex image-loading code.
7. SDL (Simple DirectMedia Layer)
Purpose: Provides cross-platform access to graphics, sound, and input devices.
Popularity Reason: SDL is broader in scope, supporting not just OpenGL context creation but also audio, input, and network functionality. Its versatility makes it a favored choice for more complex applications that require multimedia handling beyond graphics.
These libraries are popular for their specific functionalities that complement OpenGL development, making them essential tools in the toolkit of many graphics programmers. The choice of library often depends on the specific needs of the project, such as the level of control, ease of use, and the particular functionalities required.

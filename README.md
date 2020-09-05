# faberengine
Game Engine based in C++17 y OpenGL 2.1, focus in old laptops. Trying to achieve 60fps always. Using the most used tecnologies and the best techniques.

## Main Features

### Rendering 

* Parallelized forward renderer
* Programmable vertex & fragment shaders using C++ virtual functions
* Physically Based Shading
* Perspective Correct Interpolation
* Tangent Space Normal Mapping
* Ambient Occlusion mapping
* Reverse (AKA logarithmic) Z-Buffering [1,0]
* Pre-vertex shader back-face Culling
* View Frustrum culling
* Gapless triangle rasterizer 
* Fast Gamma correction
* Directional Lighting
* Bilinear Texture Filtering
* Seamless texture repeat
* Flat, Gouraud, Phong, Blinn-Phong shaders (deprecated in favor of PBR)

### Engine

* SDL2, SMTL, OpenAL and OpenGL
* Multiplatform executables
* Scene Switching
* Free moving camera 
* Orbiting Camera mode 
* Camera FOV controls
* Templated Vector Math / Linear algebra library 
* .Obj file parser
* Scene content outlined in .txt file
* Texture tiling to reduce cache misses
* Multithreading per object and vectorization within lighting shader
* Fully commented for future developments
* Image loading through [stb-image](https://github.com/nothings/stb)
* Axis aligned Bounding Box generation and reconstruction

## Known Issues

* Not work yet. Is always in development since january 2019.

# How to make opengl application in Ubuntu with CMake
## 1. Compile source code of glfw
> 1. download glfw source file.(glfw-3.3.8)
> 2. create build folder
> 3. in the build folder
>   `cmake ..`
    `make`
## 2. make a first application 
> 1. create a folder(my_opengl) for making application
> 2. create folders in that folder including `build,include,lib,src`
>3. copy compiled inlude folder from glfw to this include file
>4. copy libglfw3.a from glfw folder to the lib folder
> 4. create source file in the src folder.
> 5. create a CMakeLists.txt file
> 6. in the build folder 
`cmake ..`
`make`
`./OpenGl`
 
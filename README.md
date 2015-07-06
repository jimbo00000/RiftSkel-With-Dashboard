RiftSkel-With-Dashboard
============

A basic framework for getting started with OpenGL programming for the Oculus Rift,
plus some floating in-world UI panes.


## Description  
See the [RiftSkeleton](https://github.com/jimbo00000/RiftSkeleton) project. This project adds the floating in-world UI panes to allow more powerful interaction techniques.  


## Portability 

 - Linux, MacOS, Windows  
 - NVIDIA, AMD, Intel  

## Dependencies 
 - [CMake](http://www.cmake.org/) (for building)
 - [GLFW](http://www.glfw.org/download.html), [SDL2](https://www.libsdl.org/download-2.0.php) or [SFML](http://www.sfml-dev.org/download.php)
 - [GLEW](http://glew.sourceforge.net/)
 - [GLM](http://glm.g-truc.net/0.9.6/index.html)
 - [Oculus SDK](https://developer.oculus.com/downloads/) (optional)
 - [Sixense SDK](http://sixense.com/windowssdkdownload) (optional)
 - [AntTweakbar](http://anttweakbar.sourceforge.net/doc/tools:anttweakbar:download) (optional)

I set up my local build environment with libraries installed under a single directory(**C:/lib** on Windows, **~/lib** on Linux, **~/Development** on MacOS). This location can be changed in cmake-gui by modifying the **LIBS_HOME** variable or by editing it in CMakeLists.txt directly.

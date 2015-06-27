RiftSkel-With-Dashboard
============

A basic framework for getting started with OpenGL programming for the Oculus Rift,
plus some floating in-world UI panes.


## Description 
The skeleton app targets the OVR SDK v0.5.0.1 and provides a simple framework for developing OpenGL VR programs. Take a look at the Scene class under src/ for a basic "hello world" implementation(some simple color cubes in space).

## Portability 

 - Linux, MacOS, Windows  
 - NVIDIA, AMD

## Dependencies 
 - [CMake](http://www.cmake.org/) (for building)
 - [GLFW](http://www.glfw.org/download.html), [SDL2](https://www.libsdl.org/download-2.0.php) or [SFML](http://www.sfml-dev.org/download.php)
 - [GLEW](http://glew.sourceforge.net/)
 - [GLM](http://glm.g-truc.net/0.9.6/index.html)
 - [Oculus SDK](https://developer.oculus.com/downloads/) (optional)
 - [Sixense SDK](http://sixense.com/windowssdkdownload) (optional)
 - [AntTweakbar](http://anttweakbar.sourceforge.net/doc/tools:anttweakbar:download) (optional)

I set up my local build environment with libraries installed under a single directory(**C:/lib** on Windows, **~/lib** on Linux, **~/Development** on MacOS). This location can be changed in cmake-gui by modifying the **LIBS_HOME** variable or by editing it in CMakeLists.txt directly.

## Features 
 - OVR SDK and Client rendering paths  
 - Adaptive render buffer resolution scaling to ensure fastest possible frame rate  
 - Camera frustum highlighting when headset approaches limits of tracking area  
 - Auxiliary window with AntTweakbar controls(toggle with backtick(`) press)  
 - Tap HMD to hide Health and Safety warning  
 - Mouse click to teleport in Scene, wheel tilt for "comfort mode" rotation  
 - Sixense SDK Hydra support  
 - Keyboard and gamepad world motion support  
 - Interchangeable GLFW, SDL2 and SFML backends  

## Similar Projects 
 - [OculusRiftInAction](https://github.com/jherico/OculusRiftInAction) - Brad Davis  
 - [mutantstargoat - oculus2](http://nuclear.mutantstargoat.com/hg/oculus2/file/tip) - John Tsiombikas  
 - [osgoculusviewer](https://github.com/bjornblissing/osgoculusviewer) - Bjorn Blissing  
 - [Oculus Rift SDL2 OpenGL Demo (Updated for Oculus SDK 0.4.0)](https://forums.oculus.com/viewtopic.php?f=30&t=8948) - anarkavre  
 - [Simple OVR GLFW Example](https://forums.oculus.com/viewtopic.php?t=17842) - DoZo1971
 - [jovr](https://github.com/jherico/jovr) - Java bindings for OVR SDK - Brad Davis  
 - [python-ovrsdk](https://github.com/jherico/python-ovrsdk) - Python bindings for OVR SDK - Brad Davis  

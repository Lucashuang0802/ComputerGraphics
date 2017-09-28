# ComputerGraphics

Contains sample codes written in C language with http://www.glfw.org/, an actual implementation based on OpenGL, for grasping basic drawing knowledge.

# Installation

- Install camke: `brew install cmake`
- Install GLFW on Mac: 
    - download and extract the GLFW source codes
    - `cd` to the extracted directory
    - Issue `cmake .`
    - Issue `make`
    - Issue `sudo make install`. (The libraries will be copied to `/usr/local/lib`, the header file to `/usr/local/include`)
- Open XCode and create a Command-Line Interfadce project with C language
- Add the framework by searching `/usr/local/lib`
- Add `/usr/local/lib` to Header Search Path in XCode setting
- Hit command + B to build your program

# Credits
Huge thanks to https://www.opengl.org/archives/resources/code/samples/glut_examples/examples/examples.html for providing awesome sample codes for learning process.

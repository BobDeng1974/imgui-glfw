# imgui-glfw

[https://github.com/urddru/imgui-glfw](https://github.com/urddru/imgui-glfw)

This is a simple template project that can build a standalone [dear imgui](https://github.com/ocornut/imgui) application quickly.

```Shell

    $ git clone --recurse-submodules https://github.com/urddru/imgui-glfw.git


    # This will create the build dir and run CMake
    $ b

    # or if you don't have '.' in your PATH,  "./b"


    # Then build. Ninja is the default.

    $ cd build; ninja

```

## Features

* GLFW and Dear Imgui only - (no boost, etc.)
  * They are imported as git submodules
* Based on Dear Imgui glfw-opengl3 sample
* Minimal CMake for build generation - builds Ninja, Xcode, Makefiles, etc.
* OpenGL 3
* Tested on Mac and Linux (even Wayland)
  * Might work with minor mods on Windows


## Options

Edit the 'b' file to switch CMake generators or change other options.


## Todos

1. Simple spinning cube
2. Add more themes, break them out into a class
3. When docking lands in Dear Imgui, make sure to pull that in

## Credits

This project was inspired by a nicely done project (with more batteries included): [asap](https://github.com/abdes/asap) by [@abdes](https://github.com/abdes)

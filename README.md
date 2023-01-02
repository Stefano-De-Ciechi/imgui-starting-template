# imgui-template

A template to get started with a new imgui application (the docking branch), using GLFW and OpenGL3 as backends.

TO GET STARTED:
After cloning the repository, create two empty folders, 'tmp' and 'bin' (else the makefile will throw an error), then execute 'make' to compile all backends and imgui library files; you can now run the application using 'make run'. You can also test for memory leaks using 'make memtest' to run the application using Valgrind.

If you add any new source file or library, make sure to update the makefile accordingly!

The "entry point" of the application is the my_draw_function() in the MyApp namespace, which is called in the while(true) in the main.cpp file.

ATTENTION: This repo was generated for personal use, so it may contain errors or bad practices!

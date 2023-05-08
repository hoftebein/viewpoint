# viewpoint
View images in a specified directory

## Short description.

The program for displaying images from the current directory or the specified directory. Scrolling through images is carried out with the left and right arrow keys.

## Prerequisites.

Before compiling this application, the SFML library must be installed on your system. 

In Linux, the library can be installed with the command

```
sudo apt install libcsfml-dev
```

In Windows, the library archive must be downloaded from the [official website](https://www.sfml-dev.org/download/sfml/2.5.1/) of the developer and unpacked into a directory.

My project for Visual Studio 2022 is set to the location of the library in: C:\SFML-2.5.1

Compilation.

On Linux: go to the project directory and run the mac:

```
$ cd viewpiont
$ make
$ ./viewpoint
```

In Windows:
1. Copy all .dll files from the bin directory from the SFML library to the project directory.
2. Open the project with Visual Studio and compile.

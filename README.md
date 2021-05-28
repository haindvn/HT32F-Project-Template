## HT32F-Project-Template

Quick template for HT32F project / GNU ARM GCC
- **Src**: put your source code files here, all files in this folder will be compiled
- **Inc**: put your own include header files here
- **Makefile** (for each project): there's nothing to modify, we have common settings in Makefile.include file already, each project only need few lines in Makefile (even the project name will be automatically set to the sames as your project directory name.
	- **JLINK_DEVICE**: used for target **flash** with JLink command line utility.
- **modules_inc**: please select the modules to be compiled, we don't need to compile whole SDK everytime we rebuild (just comment out the module you need for the project, it supports incremental build).

![alt text](https://github.com/haindvn/HT32F-Project-Template/blob/main/screenshot.JPG)

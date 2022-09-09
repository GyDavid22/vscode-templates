This repository contains premade Hello world templates for Visual Studio Code with premade debug and build options.
These settings assume that you have MinGW/JDK/Python installed and added it/them to the system variables. (So it doesn't matter where you installed them.)
You can easily test if your setup is ready. Simply open a command line window and enter the following:
C/C++:
gdb --version
Java:
java --version
Python:
py --version
If you don't receive an error message when you run these commands as they are then you are ready.

The reason I made this repository is that I always had to do the same configurations for every new project, so I made premade templates and decided to share it with the world. Use these freely. Also you can delete the .gitignore files, I only needed them to keep the empty directories and keep the folder structure intact.
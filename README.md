# n-body-physics
SpaceSim Project
This project is a space simulation developed using Qt and C++.

Prerequisites
C++ compiler (GCC, Clang, MSVC, etc.)
Qt 6.6.0 or later
An IDE that supports C++ and Qt (like Visual Studio Code or Qt Creator)
Setup Instructions
1. Install Qt
You can download Qt from the official website: https://www.qt.io/download

Choose the open-source version, and during the installation process, make sure to select the correct version (6.6.0 or later) and the correct kit for your operating system.

2. Install an IDE
We recommend using Visual Studio Code or Qt Creator, but any IDE that supports C++ and Qt should work.

Visual Studio Code can be downloaded from https://code.visualstudio.com/
Qt Creator is included in the Qt installation.
3. Set up the IDE
After cloning the project, you'll need to set up your IDE to use the correct include paths for Qt.

Visual Studio Code
In Visual Studio Code, you'll need to modify the c_cpp_properties.json file (which can be found in the .vscode directory in your workspace).

Here's an example of what the includePath setting might look like on a macOS system:
"includePath": [
    "${workspaceFolder}/**",
    "/Users/username/Qt/6.6.0/macos/lib/QtWidgets.framework/Versions/A/Headers/"
]
Replace /Users/username/Qt/6.6.0/macos/lib/QtWidgets.framework/Versions/A/Headers/ with the correct path to your Qt installation.

Qt Creator
In Qt Creator, the include paths should be set up automatically when you open the project. If not, you can modify them in the project settings.

4. Build and Run the Project
Once your development environment is set up, you should be able to build and run the project using your IDE's build and run commands.

# TextFinder

## Overview
A simplified version of the Text Finder example from Qt UI Tools. TextFinder uses Qt Designer for UI construction with Qt widgets and the code editor for C++ application logic.

Feel free to reach out if you have any questions or encounter issues.

## Table of Contents
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Pre-commit Hook](#pre-commit-hook)
- [Folder Structure](#folder-structure)
- [License](#license)

## Getting Started
- Clone the repository to your local machine.
- Navigate to the "project name" folder to access the source code.
- The compiled executable (.exe/.app) can be found in the "build" folder.

## Prerequisites
- Ensure you have the latest version of Qt installed for Win or Mac: [https://www.qt.io/product/development-tools](https://www.qt.io/product/development-tools).
- Current build folders contain the .app for MacOS.
  - If you're on Windows you will need to build and run the source code to create a Win build of the application.   

## Pre-commit Hook
* Copy&paste the pre-commit file (it does not have a file ext) from templates/ to .git/hooks/ to ensure the correct file header is generated for each C/C++ file type committed back to the branch.
* A hardcoded copy of the header template is also in the templates/ dir for manual use. 

## Folder Structure
- **`Project_Name`:**
  - Folder named after the project.
  - Contains all files necessary for building the project.
  - **`CMakeLists.txt`:**
    - CMake configuration file for project building and management.
    - Used to build the entire application, assuming all prerequisites are installed.
- **`build_Project_Name_Debug`:**
  - Folder with the syntax `build_Project_Name_Debug`.
    - Contains the project along with debug configurations.
    - Useful for quick testing, but developers are encouraged to create personalized configurations for release builds.

## License
- This project is open-source and licensed under the [GNU Lesser General Public License v3.0](https://opensource.org/licenses/LGPL-3.0).
- This project may use the Qt framework, which is licensed under the [Qt Commercial License](https://www.qt.io/licensing). Please refer to the respective licenses for more details.

### Author
- [Femi Sharomi](https://github.com/femisharomi)
  
©2024 FemiSharomi 

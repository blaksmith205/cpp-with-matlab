# Graphical RLC
This repo is mostly for a Circuits 2 project. It creates a graphical UI for users to easily simulate RLC designs.
This project utilizes a C++ GUI and a connection to the Matlab engine for simulations.

## Requirements
* Matlab with Simulink installed
  * Matlab R2020a was used. Other versions should work
* Visual Studio 2017 or higher
  * Visual Studio 2019 Community edition was used.
  
## Setting up the Environment
1. Enter `matlabroot` into the Matlab command prompt to obtain the root directory of Matlab
    * Example response `C:\Program Files\MATLAB\R2020a`
2. Add MATLAB_ROOT to the environment variables with the path obtained from the above Matlab command.
3. run `git clone --recursive https://github.com/blaksmith205/graphical-rlc.git` into the git bash terminal.
4. Open up the cloned .sln file with Visual Studio.

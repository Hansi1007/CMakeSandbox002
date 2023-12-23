# Tutorial 03
CMake Konfigurieren

## 1 Windows Developer Power Shell öffnen

## 2 Mit CL von Microsoft compilieren und EXE bauen
cl /Zi /std:c++latest /EHsc /Fe: rooster.exe main.cpp<br>
PS F:\dev-workspace\sandbox\CMakeSandbox\002> cl /Zi /std:c++latest /EHsc /Fe: rooster.exe main.cpp
Microsoft (R) C/C++-Optimierungscompiler Version 19.38.33133 für x86
Copyright (C) Microsoft Corporation. Alle Rechte vorbehalten.

## 1.) mkdir build
## 2.) cd build
## 3.) cmake ..   -  Generting the Build Files / Configure the Project
## cmake ..  -G "Visual Studio 17 2022"
## 4.) cmake --build .  oder mit VisualStudio build Tool: msbuild ./projekt.sln
## 5.) ./Executable



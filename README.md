# 3Dev
Simple 3D game engine, that uses SFML, OpenGL, Assimp. 
## 3Dev Editor
3Dev Editor is in development, but now, if you on Windows, you can launch exe file in 3Dev Editor folder and make your scene.
## Tutorial
If you don't know how to make your scene, you can read small tutorial (only Russian language).
## TODO
Make Scene class

Make it cross-platform - DONE

Add lights (3Dev Editor)

Add export function (3Dev Editor)

Add simple physics

Add advanced physics

## Building test game (Linux)
In 3Dev folder you have model, skybox, code and building files. First you need to download assimp sources in 3Dev folder, execute
```
git clone https://github.com/assimp/assimp
```
int terminal, you don't need to build it. Then download and build https://github.com/1Kuso4ek1/ibs, move executable near main.cpp, then execute
```
./ibs build.ibs libraries.ibs
```
in terminal. 

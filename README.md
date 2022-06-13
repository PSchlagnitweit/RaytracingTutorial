# Raytracing Tutorial

This program is based on the following tutorial:
* https://developer.nvidia.com/rtx/raytracing/dxr/dx12-raytracing-tutorial-part-2
* https://developer.nvidia.com/rtx/raytracing/dxr/tutorial/Files/DXRTutorial_Extra.zip

## How to build
1. Clone the repository 

2. Make sure you have Windows SDK installed

3. Open D3D12HelloTriangle.sln in Visual Studion

4. Build the project

## How to jse
1. in D3D12HelloTriangle.cpp
    line 1425 (method call GenerateMengerSponge)
    change first argument to a different integer [0,4]

2. Build + run

3. Use Space button to toggle raytracing
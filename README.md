# Traffic Simulator

- SDA Final Project

## Members

- Muhammad Abdullah 21L-5288
- Safi Ullah 21L-1851

## Dependencies

- CMake (to generate makefile)
  - Install with:

```
 sudo apt install cmake
```

- GNU make (to build)
  - Install with:

```
 sudo apt install build-essential
```

- OpenGL (dependency in SFML and ImGui)
  - Install with:

```
 sudo apt install mesa-utils libglu1-mesa-dev freeglut3-dev mesa-common-dev
```

## Working enviroments

- Unix including Mac OS
- Windows will probably work but you will have to figure out how to build this yourself

## How to build?

1. Create build directory inside of the project folder: `mkdir build`
2. Open navigate into new "build" folder with terminal: `cd build`
3. Generate makefile with CMake: `cmake ..`
4. Build generated makefile: `make`
5. Run it: `./a`

## Libraries used

- SFML - Simple and Fast Multimedia Library
  - https://github.com/SFML/SFML
- ImGui - Immediate Mode Graphical User interface for C++

  - https://github.com/ocornut/imgui

- ImGui-SFML - Library which allows you to use ImGui with SFML
  - https://github.com/eliasdaler/imgui-sfml

## Resources Used

- Official SFML Documentation and Tutorials.

- Several different tutorials on Youtube.

- Pathfinding with DFS and A\* algorithm in SFML on a Tile-Based game. -https://github.com/UditSinghParihar/Pathfinding_Simulator
- ImGui tutorials by TheCherno
  - https://www.youtube.com/c/TheChernoProject
- SFML Tilemap tutorials
  - https://youtu.be/5zfsUKIynQk
  - https://youtu.be/_RLFI1D99Ow
- Excellent SFML series by Zenva
  - https://www.youtube.com/c/Zenva

---
layout: page
title: Tetris
description: Tetris game made with pure c++ and SFML
img: assets/img/tetris.png
importance: 4
category: Gameplay
---

{% include figure.html path="assets/img/tetris.png" title="cor" class="img-fluid rounded z-depth-1" %}
# **Tetris**

- **Tetris** great game, needless to say more.

## **A Tetris made with my bare hand!**
- [&#9745;] **Rotation**: Rotation of the blocks is implemented.
- [&#9745;] **Hard Drop**: Hard drop is implemented.
- [&#9745;] **Collision Detection**: Collision detection is implemented.
- [&#9745;] **Line Clearing Effect**: Line clearing is implemented.

## Control
- Left: Move Left
- Right: Move Right
- Down: Move Down Faster
- Up : Rotation
- Space: Hard Drop

## Demo:
**Demo of the engine is shown in the video below:**

[![Watch the video](https://img.youtube.com/vi/Fv8xFosL8ms/maxresdefault.jpg)](https://www.youtube.com/watch?v=Fv8xFosL8ms)

## How to run:
- Clone the repository
- Run the following command:
```bash
cmake -S . -B build
cmake --build build
./build/Tetris
```

## Dependencies:
- SFML
- CMake


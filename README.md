# Indie Studio — Bomberman

> Epitech project — B-YEP-400 (B4, *Year-End Project*)
> Team project.

A **cross-platform 3D Bomberman-like game** written in **C++** with the [raylib](https://www.raylib.com/) graphics library. The emphasis is as much on making a polished, enjoyable game as on writing clean code: 3D graphics over 2D gameplay, animations, sound and a complete game loop.

## Features

- Local multiplayer (play with a friend) plus AI-controlled bots
- Main menu to start a new game or load an existing one
- 3D graphics with 2D gameplay
- Procedurally generated maps (random obstacles and bonuses)
- Save / load a game
- Animations and sound (bomb explosions, walking, background music)
- Power-ups: Bomb Up, Speed Up, Fire Up, Wall Pass

## Tech stack

- **Language:** C++
- **Graphics:** raylib (encapsulated)
- **Build:** CMake 3.17 (generates a Makefile on Linux, a Visual Studio solution on Windows)
- **Binary:** `bomberman`

## Build

```sh
cmake -B build && cmake --build build
```

## What I learned

- Building a complete, playable game from menu to win/lose states
- Encapsulating a C graphics library behind a clean C++ interface
- Cross-platform build configuration with CMake
- Working as a team on a larger, polished project

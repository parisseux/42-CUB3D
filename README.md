  CUB3D 
-------------
<img width="1922" height="1076" alt="Screenshot from 2026-01-05 15-04-47" src="https://github.com/user-attachments/assets/dbccae66-c66a-4f5d-9c32-f510cc44cadd" />

A minimalistic 3D game engine inspired by Wolfenstein 3D, written in C.

The goal of cub3D is to understand the fundamentals of raycasting and real-time rendering by building a small 3D engine from scratch.

The program parses a configuration file, loads textures, handles user input, and renders a 3D environment using a 2D map and raycasting techniques.

## Features 
- Real-time 3D rendering using raycasting

- Textured walls with directional handling

- Player movement and rotation

- Collision detection

- Minimap rendering

- Keyboard input handling

- Config file parsing (.cub)

- Window management and rendering using MiniLibX

## Challenges & Learnings

- Implementing a raycasting algorithm from scratch

- Translating 2D maps into a 3D visual representation

- Managing floating-point precision

- Texture mapping and orientation handling

- Handling real-time input and frame updates

- Parsing and validating complex configuration files

- Designing a clean and modular architecture

## Build & Run 
git clone https://github.com/parisseux/42-cub3D.git cub3D

cd cub3D

make bonus

./cub3D maps/dungeon.cub

## Usage
WASD --> move 

space --> rune

Esc --> close window 

Mouse --> rotate POV

## Project Structure 
├── cub3d/src

│   ├── parsing/

│   ├── mlx/

│   ├── raycasting/

│   ├── utils.c

│   └── main.c

├── cub3d_bonus

├── Textures/

├── maps/

├── libft/

├── minilibx-linus/

├── minilibx_macos/

├── Makefile

└── README.md

👥 Project developed in collaboration with GauthierRohr as part of the École 42 curriculum.

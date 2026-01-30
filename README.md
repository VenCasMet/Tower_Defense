🛡️ 3D Tower Defense Game (C++ / OpenGL / GLUT)

A 3D Tower Defense game developed in C++ using OpenGL and GLUT, focusing on core game engine concepts, real-time rendering, collision logic, and progressive difficulty mechanics.This project demonstrates low-level graphics programming, manual game loop control, and system-level thinking without using any external game engines.

🎮 Game Overview

The player defends a base against incoming enemies by placing different types of towers along a predefined path.
Each wave increases in difficulty, requiring strategic placement and resource management.

The game includes:

-Multiple enemy waves

-Different tower types

-Resource-based upgrades

-Score and level progression

-Game-over conditions

📸 Screenshots

🏁 Start Screen<img width="1186" height="889" alt="image" src="https://github.com/user-attachments/assets/f01589bd-3bd8-49f6-8703-42079e9a5bd6" />

🧱 Early Gameplay<img width="1186" height="882" alt="image" src="https://github.com/user-attachments/assets/fbc35af0-c410-46d2-b916-30b06e9c2daa" />

☠️ Game Over Screen<img width="1177" height="870" alt="image" src="https://github.com/user-attachments/assets/3fc3bbf8-fffe-4b66-b97f-d2d8b08fac53" />

🧠 Core Game Mechanics

🟢 Enemy Waves

-Enemies spawn in structured waves

-Each wave increases:

--Enemy count

--Movement speed

--Damage potential

🏗️ Tower System

-Multiple tower types with different costs and damage

-Towers automatically detect enemies in range

-Projectiles are rendered and tracked in real time

💰 Resource Management

-Resources earned by defeating enemies

-Towers can only be placed if sufficient resources exist

-Strategic placement is required for higher waves

🎯 Collision Detection & Combat Logic

-Projectile–enemy collision detection

-Enemy–base collision reduces base health

-Hit detection handled manually using position checks

-Efficient logic to ensure smooth real-time gameplay

⚙️ Rendering & Game Loop

-Custom game loop using GLUT callbacks

-Frame-by-frame updates for:

-Enemy movement

-Projectile updates

-Collision checks

-Scene rendered using basic 3D primitives (cubes, cones, cylinders)

-Difficulty increases dynamically by adjusting update intervals and enemy speed.

🛠️ Tech Stack

-C++

-OpenGL

-GLUT

-Basic 3D geometry

-Keyboard input handling

-Manual rendering pipeline

-No game engines or physics engines were used.

🎮 Controls

-S – Start game

-I – View instructions

-P – Place basic tower (Cost: 10)

-S – Place standard tower (Cost: 20)

-A – Place advanced tower (Cost: 30)

(Controls can be adjusted in source code)


📚 What This Project Demonstrates

-Low-level graphics programming

-Real-time rendering logic

-Manual collision detection

-Game loop & frame management

-System design without engines

-Strong understanding of 3D coordinate systems

▶️ How to Run

Prerequisites

C++ compiler (GCC / MSVC)

OpenGL

GLUT / FreeGLUT installed

Compile & Run

    g++ main.cpp -lGL -lGLU -lglut -o tower_defense./tower_defense


(On Windows, link opengl32, glu32, freeglut accordingly.)



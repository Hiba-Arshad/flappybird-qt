# Flappy Bird (Qt / C++)

A simple Flappy Bird game developed using C++ and the Qt framework.  
The game uses Qt Graphics View to render the scene, handle animations, and detect collisions.

## Features
- Gravity-based bird movement
- Pillars generated at intervals
- Collision detection with pillars and ground
- Score counter
- Game over screen with restart option

## Controls
- **Space** → Make the bird jump
- **R** → Restart the game after Game Over

## Tools & Technologies
- C++
- Qt Framework
- Qt Creator
- QGraphicsScene & QGraphicsView

## How to Run
1. Open the `.pro` file in **Qt Creator**
2. Configure the kit if prompted
3. Build and run the project

## Project Structure
- `bird.cpp / bird.h` → Bird movement and gravity
- `pillaritem.cpp / pillaritem.h` → Pillar generation and animation
- `scene.cpp / scene.h` → Game logic, collision handling, scoring
- `widget.cpp / widget.h` → Main window and view setup
- `resource.qrc` → Game images and assets

## Notes
This project is intended for learning basic game development concepts using Qt such as graphics rendering, timers, animations, and event handling.

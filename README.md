# Beaver Jump  
[Play Here](https://emadee05.github.io/beaver-jump/)

**Beaver Jump** is a vertical scrolling platformer inspired by *Doodle Jump*, featuring custom-built gameplay mechanics, dynamic scrolling, and real-time collision physics. The entire physics engine was developed from scratch in C++ and compiled to WebAssembly for performance in the browser.

## Project Highlights

- **Custom Physics Engine in C++**  
  Simulates gravity, elastic collisions, spring mechanics, and platform interactions without using any third-party libraries.

- **WebAssembly Integration**  
  The C++ engine is compiled to WebAssembly, delivering smooth and efficient performance directly in the browser.

- **Real-Time Gameplay Logic**  
  Features seamless upward scrolling, dynamic tile generation, enemy projectiles, and responsive controls.

- **Browser-Based Deployment**  
  Fully interactive and runs in-browser using HTML5 Canvas, JavaScript, and WebAssembly. No plugins required.

## Core Features

| Feature               | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| Physics Engine         | Built entirely in C++ to simulate gravity, collisions, bounce, and springs |
| Dynamic Scrolling      | Continuously generates and removes tiles as the beaver ascends              |
| Enemy Mechanics        | Enemy invader fires random projectiles; player must dodge to survive        |
| Game Over Conditions   | Game ends upon fall or projectile hit, with falling animation and restart   |
| Score Tracking         | Live display of player height as score                                      |
| Sound Effects          | Includes audio cues for jumping, falling, and taking damage                 |
| Visual Design          | Custom pixel sprites for beaver, tiles, springs, enemies, and background    |
| Power-Ups              | Shield items grant temporary immunity from enemy bullets                    |

## Technologies Used

- C++ (physics engine and logic)
- WebAssembly (compiled C++ for browser execution)
- JavaScript (event handling and game state)
- HTML5 Canvas (rendering)
- CSS3 and Audio API (styling and sound)
- GitHub Pages (deployment)

## Run Locally

To run the game locally:

```bash
git clone https://github.com/emadee05/beaver-jump.git
cd beaver-jump
open index.html  # or use Live Server extension in VS Code

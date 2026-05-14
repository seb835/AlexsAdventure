```text
     _    _           _        _       _                 _                  
    / \  | | _____  _( )___   / \   __| |_   _____ _ __ | |_ _   _ _ __ ___ 
   / _ \ | |/ _ \ \/ /// __| / _ \ / _` \ \ / / _ \ '_ \| __| | | | '__/ _ \
  / ___ \| |  __/>  <  \__ \/ ___ \ (_| |\ V /  __/ | | | |_| |_| | | |  __/
 /_/   \_\_|\___/_/\_\ |___/_/   \_\__,_| \_/ \___|_| |_|\__|\__,_|_|  \___|
```
A Commodore 64 platform game written in 6502 assembly.

## About the Project

**Alex's Adventre** is a personal Commodore 64 game project built from the ground up in assembly language.

The main goal of this project is not just to make a game, but to finally learn how classic 8-bit games were made. Like many people who grew up with machines such as the **Commodore 64** and **ZX Spectrum**, I always wanted to understand how games were created at such a low level. Now, much later in life, I am determined to learn how to do it properly.

This project is about:

- Learning 6502 assembly
- Understanding how the Commodore 64 works
- Building a real playable game
- Working directly with memory, sprites, character sets, colours, input, and screen data
- Creating something that feels like it could have existed on a classic 8-bit computer

## Game Concept

The game is a single-screen platformer starring **Alex**.

Alex can:

- Move left and right
- Jump between platforms
- Travel from screen to screen
- Explore different rooms or areas

The game will not use smooth scrolling. Instead, each room will be a fixed screen, similar to many classic platform and adventure games from the 1980s.

When Alex reaches an exit point at the edge of a screen, the next room will load.

## Planned Features

- Single-screen platforming
- Room-to-room navigation
- Player sprite movement
- Jumping and gravity
- Collision detection
- Platforms and obstacles
- Collectable items
- Simple enemies or hazards
- Title screen
- Music

## Technical Goals

This game will be written in **6502 assembly** for the **Commodore 64**.

Planned technical areas to learn and implement include:

- C64 memory map
- Screen RAM
- Colour RAM
- Character sets
- Hardware sprites
- Joystick input
- Raster timing
- Interrupts
- Sprite collision
- Tile or room data
- Game loops
- Build automation using Kick Assembler
- Testing in the VICE C64 emulator

## Development Tools

Current tools:

- **Kick Assembler** for assembling the code
- **VICE / x64sc** for emulation and testing
- **Sublime Text** code editor
- **Git** for source control
- **Ubuntu** as the development environment

## Author

Created by Seb Pedley.

## Acknowledgements

This initial project leans heavily on the work and tutorials of Bård Baadstø Ildgruben.
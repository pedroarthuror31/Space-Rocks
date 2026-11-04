# Space Rocks

**Space Rocks** is a 2D space shooter arcade game developed using **Godot Engine 4** and **GDScript**.

Players control a spaceship and must survive the dangers of space by facing asteroids and enemy spacecraft while using movement, shooting, and defensive mechanics.

The project was created as part of my game development learning journey, exploring programming concepts, 2D physics, user interfaces, visual effects, and scene management.

## Play Online

You can play **Space Rocks** directly in your browser without downloading or installing anything.

**[Play Space Rocks](https://pedroarthuror31.github.io/Space-Rocks/)**

## About the Game

Inspired by classic space arcade games, Space Rocks offers an action-packed experience in which players must avoid obstacles, fight enemies, and survive increasingly challenging encounters.

Gameplay revolves around free movement through space, projectile-based combat, health management, and defensive mechanics.

As players progress, new challenges are introduced through the game's level progression system.

## Features

The game includes the following features:

- **Space Movement:** Spaceship acceleration and rotation mechanics.
- **Shooting System:** Projectile creation and movement.
- **Asteroids:** Space obstacles that pose a threat to the player.
- **Enemy Spacecraft:** Hostile ships that increase the difficulty of each session.
- **Health System:** Management of the spaceship's health points.
- **Shield System:** Defensive mechanics that help players survive.
- **Level Progression:** Management of levels and increasing challenges.
- **Visual Effects:** Explosions, particles, and movement effects.
- **Sound Effects:** Audio feedback for shooting, explosions, and other interactions.
- **Background Music:** Music accompanying gameplay.
- **Heads-Up Display (HUD):** Interface displaying relevant gameplay information.
- **Main Menu:** Options to start the game, view controls, and exit.
- **Controls Screen:** Dedicated screen displaying the game's keyboard controls.

## Controls

| Key | Action |
|---|---|
| `W` | Accelerate the spaceship |
| `A` | Rotate left |
| `D` | Rotate right |
| `Space` | Shoot |
| `P` | Pause / Resume |

### How to Play

1. Launch the game and select **PLAY** from the main menu.
2. Start the game from the gameplay interface.
3. Use `W` to accelerate and `A` / `D` to control the spaceship's direction.
4. Press `Space` to shoot at enemies.
5. Avoid asteroids and incoming enemy attacks.
6. Use movement and available defensive mechanics to survive.

Controls can also be viewed by selecting **CONTROLS** from the main menu.

## Technologies Used

| Technology | Purpose |
|---|---|
| **Godot Engine 4.7.1** | Game development engine |
| **GDScript** | Game logic and functionality |
| **Godot Scene and Node System** | Game component organization |
| **2D Physics** | Movement, collisions, and interactions |
| **Godot Signals** | Communication between game objects and events |
| **Particle System** | Visual effects for movement and explosions |
| **Git and GitHub** | Version control and source code hosting |

## Project Structure

```text
Space-Rocks/
├── assets/         # Images, audio, fonts, and other resources
├── bullet/         # Projectiles
├── enemy/          # Enemy spacecraft
├── explosion/      # Explosion effects
├── hud/            # Heads-up display
├── menu/           # Main menu
├── player/         # Player spaceship
├── rock/           # Asteroids
├── main.gd         # Main game logic
├── main.tscn       # Main gameplay scene
└── project.godot   # Godot project configuration
```

## How to Run the Project

### Requirements

- Godot Engine 4.7.1 or a compatible version.
- A computer capable of running 2D Godot projects.

### 1. Download the Project

On the repository page, click **Code → Download ZIP** and extract the downloaded files.

Alternatively, clone the repository using Git:

```bash
git clone https://github.com/pedroarthuror31/Space-Rocks.git
```

### 2. Import into Godot

1. Open the Godot Project Manager.
2. Click **Import**.
3. Navigate to the downloaded project folder.
4. Select the `project.godot` file.
5. Confirm the import and open the project.

### 3. Run the Game

With the project open in Godot, press `F5` to run the configured main scene.

The game should launch into the main menu, where players can select **PLAY**, **CONTROLS**, or **EXIT**.

## Development and Learning

This project was developed based on the book *Godot 4 Game Development Projects — Second Edition*, with additional implementations and customizations.

Throughout development, I explored several game development concepts, including:

- Event-driven programming.
- Scene and node-based project organization.
- Movement and physics in 2D games.
- Collision detection and handling.
- Object instantiation and management.
- Signal-based communication between components.
- User interface development.
- Integration of graphical and audio resources.

In addition to the core gameplay features, I implemented interface customizations, including a main menu with a space-themed visual design.

## Future Improvements

**Space Rocks** is an ongoing learning project, and I plan to continue improving and expanding it over time as I gain more experience with Godot and game development.

Future updates may include new gameplay features, refinements to existing mechanics, improvements to visual and audio effects, and enhancements to the overall player experience.

I intend to keep experimenting with new ideas and applying what I learn to make the game more polished and engaging.

Additional updates and improvements may be added to this repository in the future.

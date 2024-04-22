---

# Rust Roguelike Game with libtcod

Welcome to the Rust Roguelike project! This is a text-based roguelike game written in the Rust programming language, inspired by classic roguelike games like Nethack and Angband.

## Features

- **Procedural Generation**: Explore dynamically generated dungeons with each playthrough, ensuring no two adventures are the same.
- **Turn-based Gameplay**: Engage in strategic turn-based combat as you battle monsters, navigate traps, and uncover hidden treasures.
- **Permadeath**: Test your skills in a challenging environment where death is permanent, making every decision critical to your survival.
- **Character Progression**: Customize your character's abilities and equipment as you level up and gain experience throughout your journey.
- **Interactive Environment**: Interact with various objects, including chests, altars, and NPCs, each with their own unique effects and rewards.
- **ASCII Art Graphics**: Immerse yourself in a classic roguelike experience with ASCII art graphics, allowing for lightweight and accessible gameplay.

## Technologies Used

- **Rust**: Utilize the Rust programming language for its performance, safety, and expressive features.
- **tcod-rs**: Leverage the `tcod-rs` library for handling roguelike-specific functionalities like input handling, display rendering, and field of view calculations.
- **Cargo**: Manage dependencies and build processes using Cargo, Rust's package manager and build system.
- **Git**: Collaborate with contributors and manage version control using Git, ensuring a stable and well-maintained codebase.

## Prerequisites

- Rust (https://www.rust-lang.org/)
- libtcod (https://github.com/libtcod/libtcod)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/kashan16/RogueLike.git
    ```

2. Navigate to the project directory:

    ```bash
    cd RogueLike
    ```

3. Build and run the game:

    ```bash
    cargo run --release
    ```

## Controls

- **Arrow Keys**: Move the player character
- **Enter + Alt**: Toggle fullscreen mode
- **Escape**: Exit the game

## Gameplay

The game starts with the player character '@' positioned in the first room of the dungeon. The objective is to explore the dungeon, avoiding walls and obstacles, until you reach the exit or find treasure (not implemented in this version).

## Contributing

Contributions to the Rust Roguelike project are welcome! Whether you're interested in fixing bugs, implementing new features, or improving documentation, your contributions help make this project better for everyone.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This game was created following the Rust/libtcod tutorial by Herbert Wolverson (https://tomassedovic.github.io/roguelike-tutorial/index.html)

---
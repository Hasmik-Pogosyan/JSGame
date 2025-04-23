# JSGame
Javascript game. Win Condition: Hatch 30 larvae successfully.  Loss Condition: Lose more than 5 larvae to enemies.
🎮 Gameplay Overview:
🐂 Player (The Bull): Controls are based on mouse movement. The bull follows the cursor and can push away obstacles, protect eggs, and defend hatchlings.

🪨 Obstacles: Randomly placed in the world. The player must navigate around or push them to clear the way for eggs and hatchlings.

🥚 Eggs: Spawn periodically. After a short incubation, they hatch into larvae.

🐛 Hatchlings (Larvae): Must reach the top of the screen to be saved. Guide them safely!

🐸 Enemies (Toads): Slide in from the right to eat hatchlings. Prevent them from reaching their prey.

🌟 Particles: Visual effects like fireflies and sparks add feedback and polish when hatchlings are saved or lost.

🕹 Controls:
🖱 Mouse Movement: Controls the bull's direction and speed.

🖱 Click & Drag: Steer the bull around obstacles and toward eggs.

💻 D key: Toggles debug mode (collision circles, hatch timers, etc.).

🔁 R key: Restarts the game after a win or loss.

🧠 Game Mechanics:
Collision Detection: Uses circle-based physics to detect and resolve overlaps between objects (e.g., player/obstacle, egg/enemy).

Sprite Animation: Each entity uses sprite sheets for directional animations and randomized variety.

Object Pooling: GameObjects like eggs, hatchlings, and particles are cleaned up once they're no longer active.

Win Condition: Hatch 30 larvae successfully.

Loss Condition: Lose more than 5 larvae to enemies.

🧩 Features & Highlights:
Pure JavaScript – no external libraries

Modular class-based architecture

Canvas-based sprite drawing and animation

Particle system for visual effects

Real-time collision handling

Responsive mouse input

Game restart feature

💡 Ideal For:
Learning game development fundamentals with JavaScript

Practicing object-oriented programming (OOP)

Exploring canvas-based rendering and animation

Experimenting with physics and collision logic

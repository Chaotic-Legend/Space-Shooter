[![Static Badge](https://img.shields.io/badge/Godot%20Engine-4.3-blue?style=plastic&logo=godotengine)](https://godotengine.org/) ![GitHub top language](https://img.shields.io/github/languages/top/Chaotic-Legend/2D-Movement-Tutorial?logo=godotengine)

# Space Shooter | Project Touchstone #
[How To Make A Space Shooter Game In Godot 4 (Complete Tutorial)](https://www.youtube.com/watch?v=QoNukqpolS8) by [Kaan Alpar](https://www.youtube.com/@KaanAlpar) ([GitHub](https://github.com/KaanAlpar))



# Assets #
[Space Shooter Assets](https://github.com/KaanAlpar/space_shooter_tutorial/tree/main/assets) by [Kaan Alpar](https://www.udemy.com/user/kaan-alpar-22/?srsltid=AfmBOopc6_i27wdigRNqzacgR7e7PI6f2ek_Msq-WUUtZor3aF4czmn9) ([GameDev.tv](https://gamedev.tv/courses/godot-2d?ref=mzfizgj))

![Sprite Asset](assets/textures/playerShip1_blue.png)

# Create a Godot task #
<ins> What application is this task for? </ins>
<br>
Godot

### **Task prompt** ###
First, enter the **task prompt** and any relevant reference files (e.g., docs, diagrams, sketches, photos, schematics).

Tasks should sound like what a manager might give a skilled but junior employee: high-level guidance with some leeway on executional details, but with very clear success metrics. What a good outcome looks like must be very clear and easy to understand.

Include any relevant **reference files** (docs, diagrams, sketches, photos, schematics, etc) needed for someone to complete this task.

Reminder on the difference between reference and starting state files:
- **Reference files**: anything the Employee should look at or read while completing the project that does not need to be directly loaded into the application (*'please make something that looks like XYZ image'*)
- **Starting state files (upload below)**: anything that the Employee would need to load into their workspace to complete the task (*'here is the existing file you should adapt'*)

<ins> Task prompt (ask the Employee) </ins>
<br>


<ins> Which of the following best fits this task? </ins>
<br>
Task from scratch

<ins> How long would you anticipate an 'Employee' to complete this task? (in hours) </ins>
<br>
3

### **Starting state** ###
Please describe and include below any information about the starting state of this project:
- Existing work to be modified
- Other assets or other inputs the Employee needs to bring to be able to complete this task

Reminder on the difference between the starting state and the reference files:
- **Starting state files**: anything that the Employee would need to load into their workspace to complete the task ('*here is the existing file you should adapt*')
- **Reference files (upload above)**: anything the Employee should look at or read while completing the project that does not need to be directly loaded into the application ('*please make something that looks like XYZ image*')

<ins> Starting state description </ins>
<br>
The starting state file for this task includes a newly created 2D Godot project that includes a curated collection of space shooter assets, providing the basis for developing a complete arcade-style shooting game. The project will use sprite assets for a player spaceship, enemy ships, laser projectiles, power-ups, and background elements such as stars to create a dynamic space environment. To support gameplay feedback, the assets also include sound effects for shooting, hits, and explosions, as well as a sci-fi styled font suitable for UI elements. The Employee is responsible for building the space shooter game using the provided assets by setting up player, enemy, and projectile scenes with appropriate nodes, collision shapes, and animations. The Employee must implement player controls for movement and shooting, enemy spawning and behavior, projectile interactions, and power-up collection systems. This task includes defining input actions, attaching scripts to control gameplay behavior, configuring collision detection for hits and damage, and integrating audio feedback for actions such as firing and explosions. The reference files above illustrate how to use the provided assets to illustrate a space shooter game with responsive controls, dynamic combat interactions, and challenging gameplay that supports replayability.

### **Overall context** ###
Finally, include context on this task and why it is realistic and representative of real-life work:
- Why is this a reasonable task for a manager to ask a junior-level employee to do?
- Is there a larger project it might be a part of?

<ins> Task context </ins>
<br>
This task is a realistic and representative assignment for a junior-level developer, as it involves implementing core mechanics of a 2D space shooter within a structured, asset-driven game environment, including player movement, shooting systems, enemy behavior, projectile interactions, collision detection, and basic game flow. It requires applying foundational programming, problem-solving, and design skills to translate gameplay requirements into functional systems while integrating movement, combat mechanics, visual feedback, audio cues, and user input into a cohesive experience. This project mirrors typical real-world development practices, in which developers prototype new gameplay styles, structure scenes and assets, and build systems in a modular, extensible manner to enable future growth and enhancements. By defining the core gameplay idea, this task creates a modular framework to support upcoming features, including expanded enemy variety, new weapons, equipment upgrades, and more UI elements.

<ins> Rubric Items </ins>
<br>
1. The spaceships, level background, and level props all appear sharp.
- Run the main scene and observe that all spaceship sprites, level background, and environment props appear sharp and clear.
- The task prompt requires that all spaceship sprites, level background, and level props remain visually sharp and clear.

2. The player character is a small blue and grey spaceship with wings.
- Run the main scene and observe that the player character appears as a small spaceship that's colored blue and gray.
- The task prompt requires a small spaceship with blue and gray colors for the player character sprite.

3. The background is outer space with purple stars and moving particles.
- Run the main scene and observe that the level background displays outer space with purple stars and fast-moving particles.
- The task prompt requires that the level background display as outer space with purple stars and fast-moving particles for effect.

4. The player properly collides with the environment, enemies, and walls.
- Run the main scene and move the player character across the level to confirm it collides with enemies and the level's border walls.
- The task prompt requires functional collision bodies for the player character to interact correctly with all level environment elements.

5. The camera displays the player character accurately during gameplay.
- Run the main scene and move the player character across the level to confirm that the camera accurately displays the game vertically.
- The task prompt requires a game camera to maintain a consistent vertical view of the gameplay and display the player character.

6. The player moves in all directions and stops when input is released.
- Run the main scene, move the spaceship in all directions with the arrow keys, then release the keys to confirm it stops immediately.
- The task prompt requires the arrow keys for movement, and the player character will stop immediately upon releasing the input.

7. The player character can shoot red lasers and play a sound effect.
- Run the main scene, press the Space key, and observe the player character fire red laser projectiles and play a shoot sound effect.
- The task prompt requires the player character to shoot red lasers and play an appropriate sound effect for the laser projectiles.

8. Fast-moving enemy spaceships are destroyed by one laser projectile.
- Run the main scene, locate a fast-moving enemy spaceship, and shoot it once to confirm that the player character destroys it.
- The task prompt requires fast-moving enemy spaceships to be destroyed by a single laser projectile.

9. Slow-moving enemy spaceships get destroyed by two laser projectiles.
- Run the main scene, locate a slow-moving enemy spaceship, and shoot it twice to confirm that the player character destroys it.
- The task prompt requires slow-moving enemy spaceships to be destroyed by two laser projectiles.

10. Enemy spaceships register hits from lasers and play a hit sound effect.
- Run the main scene, shoot any enemy spaceship, and observe that each hit registers and plays a hit sound effect.
- The task prompt requires enemy spaceships to take hits and play a hit sound effect when struck by laser projectiles.

11. The player can crash into enemies and play an explosion sound effect.
- Run the main scene, collide the player character with an enemy spaceship, and observe that an explosion sound effect plays.
- The task prompt requires that the player character can collide with enemies and trigger an explosion sound effect.

12. A score counter updates when the player destroys enemy spaceships.
- Run the main scene, destroy enemy spaceships to earn points, and observe that the score counter increases accordingly.
- The prompt requires a score counter UI at the top that accumulates points when the player destroys enemy spaceships.

13. Fast enemies give 200 points, and slow enemies give 100 points.
- Run the main scene, destroy both enemy types, and observe that fast enemies give 200 points and slow enemies give 100 points.
- The task prompt requires that fast-moving enemies award 200 points and slow-moving enemies award 100 points.

14. The space game can shut down when pressing the Escape key.
- Run the main scene, press the Escape key, and observe that the space shooter game closes immediately.
- The task prompt requires the space shooter game to shut down when the player presses the Escape key.

15. The game resets when pressing the R key or after the player crashes.
- Run the main scene, press the R key to verify the game resets, then collide with an enemy to confirm the player can reset the game.
- The task prompt requires the game to reset when the player presses the R key or when the spaceship crashes into an enemy.

16. A game-over screen displays the final score when the player loses.
- Run the main scene, lose the game with some points, and observe that a game-over screen displays with the accumulated score.
- The task prompt requires a game-over screen UI that appears when the player loses and displays their total score.

17. A high score tracker displays and updates on the game-over screen.
- Run the main scene, achieve a new high score, and observe that the high score updates and displays on the game-over screen.
- The task prompt requires a high score tracker that updates and displays the player's highest score on the game-over screen.

18. The enemy spaceships spawn from the top and move downward.
- Run the main scene and observe that enemy spaceships spawn from the top and move downward at different horizontal locations.
- The task prompt requires enemy spaceships to spawn from the top of the screen and move downward at varied positions and intervals.
<br>
Godot - https://feather.openai.com/tasks/c5ef53e1-fc47-4853-9f11-68613211fe7c/stage/prompt_creation - Awaiting response.

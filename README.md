# GAME360-Task2-Delecluse
# Task 2: Singleton Implementation
## Student Info
- Name: Daxton Delecluse
- ID: 01255083
## Pattern: Singleton
### Implementation
The singleton pattern was implemented via the GameManager script in Unity. The Game Manager handles methods across the whole game, from the quit button to the scoring system. Every object in the game communicates with the game manager to allow for a smooth experience. Considering the infinite amount of enemies that can spawn, the singleton pattern was necessary so that there weren't dozens of scripts running at the same time. Instead, they are all communicating with one object in the game. The game manager is also in charge of reloading the game, and is useful for making sure the game reloads all assets properly.

### Game Integration
The game manager is implemented in the game because it is, like said before, in charge of nearly everything. It controls how the game loads, keeps score of everything, manages how the player loses lives, checks when collectibles are picked up, and then accurately updates the UI to track all of that. Every single method the game could ever need is located in the game manager (except for a select few). Because of this, the game manager is the only object in the game that needs to be kept between loads, as it can reload everything else on its own.

## Game Description
- Title: Space Marauders
- Controls: WASD for Movement, Click to Shoot
- Objective: Survive as long as possible against the enemy ships. Shoot them to score points.

## Repository Stats
- Total Commits: 5 (including the one with this README)
- Development Time: 6 hours

## Side Note
This task was confusing to me. It reads like we were supposed to make our own separate project, but the assets on Canvas and tutorial videos seem to want us to follow them completely? Also, the task description says to start with git implementation from day 1, but the tutorial video for git implementation was released on the last week of the task. Why not include the tutorial in week 4?
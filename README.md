# Final_AnthonyPointer_Spring2026# Puss in Boots in the Phantom Maze

## Game Overview
Puss in Boots in the Phantom Maze is a 2D horror maze game made in Unity 6.  
The player controls Puss in Boots and must explore a haunted maze while avoiding ghosts.

The objective is to:
- Collect all 4 keys
- Avoid the ghosts
- Reach the exit door before time runs out

---

# Features

## Player System
- 2D player movement
- Animated player character
- Flashlight effect
- Footstep particle effects

## Ghost AI
- Multiple ghosts patrol the maze
- NavMesh movement system
- Ghost collision kills the player
- Ghost ambient sound effects

## Key Collection System
- 4 collectible keys
- Key counter UI
- Exit door unlocks after collecting all keys
- Key pickup sound effects

## Timer System
- Countdown timer
- Lose condition when timer reaches zero
- UI timer display

## Win / Lose System
- Win screen after escaping
- Lose screen when caught by ghosts
- Audio stops on death or victory
- Game freezes after ending

---

# Unity Components Used

## Core Components
- Rigidbody2D
- Collider2D
- AudioSource
- SpriteRenderer
- ParticleSystem

## Unity Systems
- NavMeshSurface
- TextMeshPro
- Animator
- Canvas UI

---

# Main Scripts

## PlayerMovement.cs
Controls:
- WASD movement
- Character movement speed
- Rigidbody2D movement

## PlayerDeath.cs
Handles:
- Ghost collision
- Player death
- Lose screen
- Stopping all sounds

## KeyPickup.cs
Handles:
- Picking up keys
- Updating key counter
- Unlocking exit

## TimerManager.cs
Handles:
- Countdown timer
- Updating UI
- Triggering game over

## GhostSound.cs
Handles:
- Ghost audio loop
- Stopping sounds on death/win

---

# Controls

| Action | Key |
|---|---|
| Move Up | W |
| Move Down | S |
| Move Left | A |
| Move Right | D |

---

# Game Goal

1. Enter the maze
2. Avoid ghosts
3. Collect all 4 keys
4. Unlock the exit
5. Escape before time runs out

---

# Assets Used
- Unity 6
- TextMeshPro
- Universal Render Pipeline
- Puss in Boots sprite assets
- Audio clips for keys and ghosts
- Particle effects

---

# Creator
Anthony Pointer  
Spring 2026 Final Project

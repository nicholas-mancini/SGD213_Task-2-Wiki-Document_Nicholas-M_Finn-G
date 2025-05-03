# Justification

## Overview

### Brief
[//]: # (What was the client's brief?)
The client is looking for a 2D sidescrolling platformer
* The client should be able to easily customize the level, enemies, pick ups, and control the player
* The client will focus of the art for the game
* The gameplay should be similar to the classic mario games
* The player should be able to walk, run, jump and be damaged

### Communication
* When do you need this prototype by?
> I expect it to be completed by June 1st.

* Would you prefer the prototype be made in 2D or 3D?
> 2D is okay for the prototype.

* Do you want a menu or UI for multiple levels?
> A simple main menu with Start/Exit is sufficient, though a Level Select would be a good addition provided it can be made in time.

* What level parameters do you want to be able to customize? (gravity, drag, etc.)
> Most of the variables that should be customized are already exposed in the Rigidbody component, though I do expect most variables that the player controller uses to be exposed in Editor.

* What mechanical terrain types do you want implemented? (slippery ground, slopes or blocks, water, etc.)
> Slopes are a must, and I'd like to have water for the level design variety. However, it should also be treated as something of a stretch goal

* What mechanical obstacles/objects do you want implemented? (out of bounds kill box, spikes, pot/chest, etc.)
> Spikes and pits the player can fall into would both be excellent additions, which would require an out-of-bounds killbox.
    
* What types of enemy actions would you like? (throwing things, jumping, etc.) / How do you want the enemies to act? (walk back and forth, chase the player, etc.)
> For enemies, I would want a couple of simple entities for the prototypes, mostly patrolling or chasing the player on certain platforms.
    
* How do you want enemies to spawn? (placed in level creation, random spawn, etc.)
> They would be placed in level design and spawned in from stationary spawners.
  
* How do you want pick-ups to act? (stationary, move, time limit till despawn, etc.) / How do you want pick-ups to spawn? (placed in level creation, random, when the player does something, etc.)
> For pickups, I would want them to be placed in level design and be stationary.
  
* What do you want the pick-ups to be able to change? (speed, jump, give new action type, etc.)
> For the prototype, a simple speed pickup would suffice, though a double jump would also be excellent to have time permitting.

* Are there any other actions you want them to do? (attack, double jump, etc.)
> Being able to double jump would be a great addition to the player controller. I don't see the player attacking directly, outside of the classic Mario maneuver of jumping on top of enemies.
  
* What other movement types should they have? (swim, fly, etc.)
> No other movement types would be required: should the water be implemented, I'd expect it slow the player down and prevent them from jumping but not be something they can dive under.
  
* What inputs do do you want the actions to use? (WASD, mouse, controller, etc.)
> I would like the prototype to be playable with a keyboard, though if you could add controller support as a stretch goal it would an excellent addition.
  
* What player parameters do you want and which should be customizable? (health, speed, size, jump height, etc.)
> All the player parameters you've listed are something I expect to be exposed in Editor and customizable.
  
* When the player dies how do you want them to respawn and are should there be check points? (instant respawn, puts player in menu, etc.)
> Check points with instant respawn sound great!
  

---

## Project Understanding

### Requirements
[//]: # (What are the requirements of the finished project?)
* Needs the product by June 1st.
* Must be a 2D sidescrolling platformer
* Needs a main menu with start and exit functionality
* Levels must be easily created in editor
* Player variables must be exposed in editor
* Player must be able to walk, run, jump and be damaged
* Player inputs must use keyboard
* Player must be able to kill enemies by jumping on their head
* Enemies must be built to easily create different types
* Enemy types to create: patrolling (back and forth) and chase player
* Enemies must be placed in editor and spawned from stationary spawners
* Required terrain types: slopes and flat platforms
* Required obstacle types: spikes and pits (use out of bounds kill box)
* Check point object to set player respawn. on death player must instant respawn at last checkpoint
* Pick ups must be built to easily create different types
* Pick ups must be stationary, placed in level editor
* Required pick up types: speed boost

Stretch Goals to implement (not required)
* Level select in main menu
* Water terrain type, must slow down player
* Player movement swimming type, player can not jump or dive under, only swim on the waters surface
* Double jump movement type, allowing the player to jump again mind air, but only once after jumping off the ground
* Double jump pick up
* Controller input support

### Expectations
[//]: # (What are the client's expectations?)
* Project delivered on time
* Project completed with all requirements met
* Project completed with as few major bugs as possible
* Weekly updates on progress
* Communication with the client when design issues encountered or when greater detail on specifications is requried
* Communication with the client about how the project will be handeled and created
* Quality transparent project management (add the client)
* Temporary assets used and replacable by client

### Assumptions
[//]: # (What are you assuming based on client responses)
* UI art does not need to be high quality, will just use a collection of free sprites and basic geometry
* Sound was not mentioned in the request, so if added it will not need to be high quality
* Client asked for a main menu, it likely also needs to be acessable during gameplay so the player can quit if they wish. Similar to a pause menu
* No mentions of sprite animations were made, however they were informed that free art assets would be used to test animation functionality, so they will likely be required
* The client metioned terms like 'Ridged Body' so when communicating it can be assumed the client has a decent understanding of coding a game and explaining terms will not be required unless requested
* Based on the terrain types and the request for easy level building, the client likely wants the game objects to be tileable in a grid fassion
* Key board inputs will be assumed to use standard WASD or arrow keys as well as the shift key to sprint
* There should be a cap on how many enemies can spawn, to prevent a crash from too many entities

---
## Risks

### Risks
[//]: # (What are the risks of this project)
* Unity and C# are excellent prototyping tools, but working quickly often means less than perfect code
    * Project may not be fit for use in further development
    * Bugs may be present in prototype due to the short turn-around
    * Working quickly is error-prone
* The client wants many features of varying complexity in a short time frame, some specifications may not be completed on time
* The Amazings Dev Team only has two members
   * Increasing the amount of work each will be required to do
   * Limiting the pool of coding knowledge to complete or fix specifications
   * Limiting time avalable for communication with client
* Memebers of the dev team have limited time due to other tasks to be completed
* Time may be wasted if both members try to code the same functions with out the other knowing
* Coding can not be done on a shared document so the other members might not always have the most recent versions of a file
   * Creating potential bugs
   * Possibly creating miscommunication

### Risk Management
[//]: # (How are you managing the mentioned risks)
* All coding will aim to be designed in an extensible manner
* Testing will be undertaken throughout prototype development
* Using source control we will ensure our code is safe and usable at all times
* Planning the most effecient order to code each script, and completeing the most important scripts first
* Dividing the work load evenly, with clear communication between members
* Using resources to to find solutions to issues that neither member know how to fix
* Setting aside weekly time to communicate with client
* Clear communication on each members time avalible for the task, and when they will be working on which script
* Consisnent and regular sharing of updated work
* Scripts that require other scripts should be grouped with and worked on by the same member where possible

---

## Constraints

### Constraints
[//]: # (What are the constraints of this project)
* We have a tight timeframe, so we will need to make fast decisions, which may be less than perfect
* The time we have may be limited further based on other classes and assignments
* Less extensive coding knowledge than would be preffered, which will limit the quilty and spped of the projects creation
* Code created will not be automatically updated for the other member, leading to a difference in completion between members if not shared
* Finding time where both members are free to discuss any nessecary information

---

## Justification
We liked the idea of working on a classic platformer similar to the older Mario games and thought we could make something similar. The goal will be to complete all the required specifications, however, if those are completed, we would like to work on some other mechanics from the stretch goals and maybe more. Since what we called the project didn't matter too much, being changeable by the client later, we decided to make it relate to the request for a Mario style game but make a joke about it not being exactly that. As such we came up with the name Legally Not Mario

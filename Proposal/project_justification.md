# Justification
[//]: # (This section is an example of justifying your design and development decisions.)

## Overview

### Brief
[//]: # (What was the client's brief?)
The client is seeking a proof of concept for a game that is simple, yet a leader in its class
* Users should be drawn to the game by its eye-catching visuals
* The audio in the game should be exciting and drive the player's emotion
* The gameplay should be fast-paced, quick to gain feedback and quick to retry

### Communication
* When do you need this prototype by?
> I need the prototype by Friday Week 13.

* What kind of games do you think are good?
> Couch coop games appear to be simple enough to develop and can move reasonable units if done well.

* Since you only need a prototype, are you happy for us to focus on gameplay and use based geometry for art assets?
> Yes perfect, the prototype is a proof of concept, please don't waste time on creating art assets; if the game is fun with simple art assets, that is perfect. At least change the colour palette to be aesthetically pleasing though.

* Do you need a menu system?
> Well I need to be able to take this to potential investors to sell the idea. If I need to quit out of it every time I finish that will not work. It will need basic UI functionality, pausing, quitting out of game, exiting the application, returning to main menu, playing the game from main menu.

* Are there any themes you think are popular or you would like to see in your game?
> Hmm... not really. I do like dragons though! I think silly games catch people's eyes?

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
We really like the mention of "silly games catch people's eyes". So we took your suggestion of dragons and built on it with alliteration as a starting point. We went through many ideas, but finally came up with a title called "Donuts, Daggers & Dragons.

The name along was enough to get conversation happening, and we soon found ourselves thinking of countless, comical and enjoyable scenarios stemming from the title.

etc. Explain your design decisions in regards to the client's requirements.

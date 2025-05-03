# Project Overview
[//]: # (This section is an example structure for the proposal to your client.)

>This is all sample material in here, to give you an idea on how and what to populate each section with. If you think of other sections or a different document layout, please do use it!

## Design
[//]: # (How will you meet the client's brief, their expectations, and their requirements.)

### Project Name
Not A Mario Game

### Description
[//]: # (This is the elevator pitch, sell the idea)
Players play in a 2D sidescrolling platformer similar to the classic Mario games. Walking, running and jumping their way through the level, players must avoid obstacles and or detroy the enemies else they kill the character and respawn them. They can find check points to set there spawn or collect pick ups for a temporary power boosts.

### Begin Date
4th of May

### End Date
1st of June

### Justification
Read the design justification [here](project_justification.md).

---

## Statement of Works
[//]: # (This section is about managing expectations; list out all of the qualities that will be in the final product)

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

[//]: # (### Schedule of Rates)
[//]: # (This is where you would list your hourly rates and time estimations)

## Milestones
[//]: # (Breakdown of phases of development, with estimated delivery times)
[//]: # (In practice, if you were working on fixed price phases, you would also list expected payment after each phase.)
| Phase | Completion Date |
| --- | --- |
| Menu and Foundations | Week 10 |
| Player and Terrain | Week 11 |
| Enemies and Pick ups | Week 12 |
| Prototype Completion | Week 13 |

---

## Team Member Info
| Team Member | Student ID No. |
| --- | --- |
| Nicholas Mancini | 1154237 |
| Finn | Number |

## Agreement
[//]: # (List out the arrangement)
Work will be completed to fit the provided Statement of Works, any work outside of this arrangement will be billed at our hourly rate, or, quoted separately.

## Signatures
[//]: # (If dealing in person, agreements should be signed so that additional work can be billed)
| Client Name | Date | Signature |
| --- | --- | --- |
| John Doe | 12-34-5678 | ________ |

| Team Rep. | Date | Signature |
| --- | --- | --- |
| Jane Doe | 12-34-5678 | ________ |

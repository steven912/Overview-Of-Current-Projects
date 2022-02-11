# Overview Of Current Projects

A visual tour of some projects I've worked on.

-----

### Bug Wars
#### Status: On Hold


<img src="https://user-images.githubusercontent.com/27746512/153512879-7962edbd-6b42-48e9-83d7-28b0f60c9d6b.gif" width="70%" height="70%"/>

#### How to Play:

  Take control of a brainbug fighting to find his queen that was kidnapped from him! Using psychic brain energy, brainbugs control insects around them into hives. Battle enemy brainbugs and their hives using mana-costing ability cards, distributing energy into FTL-like systems that give different benefits, and setting your own hive out to do battle! Includes a sophisticated charm system as well.

#### Dev Description:

  Probably my most developed project, but also suffering from scale creep and loss of vision/excitement. I spent so much time creating all these systems, and once they were created and the next step was to flesh them out with ideas, I got hit with something exactly like writer's block. There are just too many options in front of me of how the game could play, that I'm kind of paralyzed with indecision. Regardless, I'm proud of the progress of this game, as over the course of it I really felt I was becoming a significantly better developer. 

#### Influences:

  - FTL for the systems and broad crew dynamic in the summoning of bugs to fight for you
  - Starship Troopers for the bug aesthetic
  - Slay the Spire for the card influences

#### Next Steps:

  - Defining significant gameplay choices and doggedly pursuing them, regardless of potentially waning enthusiasm levels

-----

### Pirate FTL
#### Status: On Hold

<img src="https://user-images.githubusercontent.com/27746512/153533227-ca97d446-4f0d-4217-a213-dadff2899fda.gif" width="70%" height="70%"/>

#### How to Play:

  Take control of your ship and roam the high seas in this spiritual successor of FTL! Command you crew and battle adversaries, but choose their fate carefully, because your actions will be remembered by them the next time you meet. Control your systems, manage your crew, and cycle through your cannons to defeat the enemy and claim their plunder!

#### Dev Description:

  This is meant to be an improved and modernized version of FTL, and its alright. I've almost completely remade base FTL, I'm only short the crew manning systems dynamic and the drone systems and shop menus, but everything else is solid if a little buggy. I completely redeemed myself AI and pathfinding wise from my earlier catastrophic attempts in games like Stormbringer, but I still made a mistake in building it like a pure tile map, when in reality the crews move through and stay in rooms, not specific tiles the user picks. That was a lack of foresight that I've since improved. Also, the UI and player clicking system in this game is very well done and thoroughly planned, so good job me.

#### Influences:

  - FTL
  - Shadow of Mordor, for the rough rival inspiration

#### Next Steps:

  - Finish recreating FTL base mechanics 

-----

### IPS: Intergalactic Parcel Service
#### Status: Complete Code Revamp Needed


<img src="https://user-images.githubusercontent.com/27746512/153536266-096188fc-40b4-4254-90b4-06003830adf3.gif" width="70%" height="70%"/>

#### How to Play:

  Take control of a minimum-wage worker working in the floating space retail package distributor IPS! Engage with and provide friendly customer service to your alien customers while completing their orders, which can consist of tasks such as: package scanning, making copies, laminating, stamping postage, scanning fingerprints, faxing, distributing mail into mailboxes, collecting packages, and more!

#### Dev Description:

  A game directly inspired by my experience working in a UPS store, the customer interactions I experienced, and the tasks I had to complete while working there. This was the first in-depth game I made, and its code reflects that, in that it’s a huge mess that I don't understand and, while it all worked at one point, would need to be completely redone. The general experiences of the game, the character and environment designs, and the story are all documented and IMO entertaining, so I would love to take another crack at this while being so much more experienced in coding (like knowing what a singleton is or how queues can be used lol).

#### Influences:

  - Papers Please for general gameplay
  - Real life UPS store experiences

#### Next Steps:

  - Complete code reimagining

-----

### Shape Escape
#### Status: On Hold

<img src="https://user-images.githubusercontent.com/27746512/153460421-d892cf30-dc3a-4c08-b1af-bcced7f72837.gif" width="20%" height="10%"/>

#### How to Play:

  The player controls a red ball in a 2D space. By dragging and releasing the ball, it launches in that direction. While launched, pressing down again makes the ball attempt to anchor to the wall, but only if an anchorable material is in front of the ball (in the gif, white parts are attachable). Different prefab wall sections are spawned and de-spawned as the player rises so that no two playthroughs are ever the same. Lava chases the player and accelerates over time, and if it catches the player it's game over.

#### Dev Description:

  I made this for Intro to Gamedev's second prototype project. I aimed to make a simple, fun, and quick mobile game that the user could pick up and put down easily. I think I achieved that goal, as all the reviews I received from friends and family were similar to that aim (without me letting them know what my goal was).

#### Influences:

  - The 'Pokio' bird capture from Super Mario Odyssey

#### Next Steps:

  - Polishing and fleshing out gameplay features
  - Working with an artist to develop a polished aesthetic
  - Publishing

-----

### Wemm Wrangler
#### Status: On Hold


<img src="https://user-images.githubusercontent.com/27746512/153467565-c59bde20-95da-42ce-bc00-401d9695aa4c.gif" width="60%" height="60%"/>

#### How to Play:

  The player is given a set number of Wemms (nonsensically titled little guys) per level, with the goal of getting one into the 'golden zone' to win the level and progress to the next. Dragging back on the right-most Wemm will launch it forward in a zero-gravity space environment, and if it exits the screen it is destroyed. Obstacles in the way include planets and their gravity fields, teleporters, kill zones, etc. 

#### Dev Description:

  My goal for this was to make a heartier mobile game. I tried to make it still quick and easy to stop and start, but at the same time have more meat than a game like Shape Escape.  I think the base is pretty solid, with the only problem being that the way I have gravity fields coded right now feels... not clunky but inexact? Wemms when shot through a gravity field feel random in their trajectory, which isn't satisfying. A potential solution is to project their movement via some kind of line render, but I don't know how to get the lines to simulate physics effects without absolutely tanking the performance of the game. Awkward situation!

#### Influences:

  - Mario Galaxy for the gravity and space themes
  - Angry Birds (or the medieval flash game its based on) for the launching of Wemms and limited tries and level layouts 
  
#### Next Steps:
  - Determine solution to trajectory aiming problem
  - Flesh out gameplay

------

### Untitled Pokémon GO Clone
#### Status: Super Early Prototype

<img src="https://user-images.githubusercontent.com/27746512/153491161-f1a6e3ee-f5e5-4d6a-9634-dab2abedb1a9.gif" width="50%" height="50%"/>

#### How to Play:

  Walking around gives the player storable encounters with Pokémon, that when pressed allows the players to try and catch the Pokémon to have in their inventory.

#### Dev Description:

  This game plays similar to Pokémon GO, with several small but solid changes. One, instead of an overworld map, the player generates encounter cards by walking that are then stored for the play to use whenever. Two, Pokémon are 2D sprites instead of 3D models. These changes make the game doable on a small scale and allow the user to try to catch their Pokémon whenever, instead of having to have their phone out all the time while they're outside. That being said, encounters can be granted for anything, not just steps. It could be safe elevated heart rate tracked via Fitbit integration, or days gone to the gym, or days sober, or days meeting their diet, etc.

#### Influences:

  - Pokémon GO

#### Next Steps:

  - Develop sophisticated prototype and further planning


-----

### Games too Messy/Incomplete/Corrupted to Show:

#### Stormbringer
##### Status: Complete Revamp Needed

  This was done in an early version of unity and all the prefab assets were lost in it. Beyond that, it was my first attempt to make any type of AI, and I was a complete amateur when I started. Learned a lot about pathfinding and state machines and tile sets, but honestly it was pretty disgusting code so I'm not too upset to lose a lot of the data.


#### Through The Page
##### Status: Early Prototype

  My first serious attempt at making a game. It's a Binding of Isaac clone about a bee, and that's about all I had lol. I managed to get a character moving up and down and left and right before losing interest. 




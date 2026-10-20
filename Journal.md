## Wednesday Team Meeting September 17

On Wednesday, our team focused on developing a set of questions to better understand the requirements and expectations for the **CART 415 Large Crowd Game Project**.

We reviewed the initial project brief and identified several areas that needed clarification, including:

- The purpose of using **phones and QR codes**
- How players would connect to the game
- The expected number of simultaneous players
- Whether the experience would be **web-based, software-based, online, or offline**

We also discussed different gameplay possibilities, such as:

- Each player controlling their own character
- Everyone controlling a shared character
- Using individual usernames or character designs
- Deciding whether the experience should have a clear beginning and end or run continuously

Another important part of our discussion was the project's **physical and artistic direction**. We considered questions such as how large the projected display would be, whether the project would be designed specifically for the classroom or a larger exhibition space, and how much of the project the CART 415 students would be expected to implement.

# Journal Entry: Brainstorming Game Ideas

On Wednesday, September 23, we met with our client, Jonathan, to clarify whether the project would be a demo for CART 415 students or a game they would continue developing. We learned that the students would build on the game, so our goal is to create a prototype for CART 415.

Our first step is to brainstorm possible game concepts. At our next class, each team member will present their ideas, and we’ll discuss how to select and combine them.

We also began organizing different possible approaches to player connection and gameplay, including **QR codes, join codes, smartphone controllers, motion controls**, and experiences that do not require phones.

Overall, our work on Wednesday focused on identifying the project's major uncertainties and preparing questions that would help us better understand **Jonathan's vision** before proposing specific solutions.

# Game Ideas

## 1. Hold the Item

A multiplayer arena game where players compete to hold a special item for a set amount of time. One player starts with the item, while everyone else tries to knock it loose, steal it, or disrupt the holder. Whoever holds the item long enough wins.

**Possible features:** The item could grant temporary powers, arenas could have hazards, and players could use defensive or disruptive abilities.

## 2. Multiplayer Crossing Challenge

A large-scale take on *Frogger* or *Crossy Road*. Players race across a dangerous course filled with moving obstacles, gaps, and hazards. They can bump into or block one another to slow their rivals down.

**Goal:** Travel farther than anyone else before getting knocked out or running out of time.

**Possible features:** The course could change as players progress, with new hazards appearing and temporary paths opening or closing.

## 3. Big Ball Soccer

Players are divided randomly into two teams and try to push a giant ball into the opposing team’s goal. Anyone can join, allowing the teams to grow very large.

**Goal:** Work together to move the ball across the field and score before the other team does.

**Possible features:** Add power-ups, obstacles, or special roles that help players defend, attack, or control the ball.

## 4. Choose Your Path Adventure

Players experience a shared adventure by voting on what the main character should do at key moments. The option with the most votes determines what happens next, so the group shapes the story together.

**Possible features:** Choices could lead to branching paths, unexpected consequences, puzzles, or encounters that require teamwork.

## 5. Tower-Building Jenga

Players work together to build the tallest possible tower by pushing or placing brick blocks. Each move could make the structure less stable, turning the building process into a giant multiplayer Jenga game.

**Goal:** Keep the tower standing while making it as tall as possible. If it collapses, the players restart.

**Possible features:** Players could take turns, compete to make risky moves, or earn points for adding blocks without causing a collapse.

## 6. Grand War

A large-scale team battle inspired by games like *Worms*. Players join one of two teams on a destructible battlefield and use different weapons or abilities to outplay the opposing side.

**Goal:** Defeat the other team through strategy, teamwork, and well-timed attacks.

**Possible features:** The battlefield could change during the match, and players could choose different weapons, classes, or tactics.

## 7. Giant Boss Raid

A cooperative boss battle where a large group of players joins an ever-growing party to take down one enormous creature. Players need to coordinate their attacks, avoid the boss’s abilities, and support one another.

**Goal:** Defeat the boss before the party is overwhelmed.

**Possible features:** The boss could have multiple phases, weak points, and attacks that require players to work together or split into groups.

# Multiplayer Game Concept Development

**Date:** October 6, 2026

## Overview

During this stage of the project, I focused on developing and evaluating several possible concepts for the large-crowd multiplayer game. The main goal was to explore how different gameplay ideas could take advantage of a large and unpredictable number of players joining and leaving the game through their smartphones.

## Multiplayer Concepts

I developed four main multiplayer concepts:

1. **Tower-Building Jenga Game**
2. **Giant Ball Soccer / Giant Puck Hockey**
3. **Multiplayer Goalie Challenge**
4. **Dynamic Maze Game**

For each concept, I explored how players would connect to the game using a **QR code**, how the gameplay would change depending on the number of active players, and how players could interact with one another within a shared environment.

## Player Count as a Gameplay Mechanic

A major idea that emerged from this process was treating the **number of players as a gameplay mechanic rather than simply a technical limitation**.

For example:

- In the **Jenga concept**, having too few players makes managing the blocks difficult, while having too many players creates coordination and collision problems.
- In the **giant ball or puck concept**, the number of players directly influences which team has control over the object.
- In the **goalie challenge**, more players create more opportunities to score while also increasing the amount of chaos on the field.
- In the **maze concept**, the number of players could potentially influence how the environment changes.

This helped establish the idea that the game should not necessarily require a fixed number of players. Instead, the game could adapt to the number of people participating.

## Gameplay, Connectivity, and Technical Evaluation

After developing these concepts, I compared their **gameplay, connectivity, and technical advantages and disadvantages**.

Some of the main challenges I identified were:

- Network synchronization
- Physics calculations
- Player collisions
- Team imbalance
- Excessive chaos
- Managing players joining and leaving
- Handling disconnected players
- Keeping the game understandable for new players

This evaluation helped me identify which parts of each concept could become difficult to implement and which mechanics could make the multiplayer experience more engaging.

## Potential Solutions

I then explored potential solutions to these problems. Rather than trying to completely eliminate the chaos created by large numbers of players, I considered ways to make the chaos part of the intended gameplay.

Some potential solutions included:

- Dynamically adjusting difficulty based on player count
- Simplifying physics calculations
- Limiting the number of active objects
- Using cooldowns for player abilities
- Allowing players to switch teams
- Dynamically changing the game environment
- Scaling the number of objects or events based on the number of players
- Allowing eliminated players to continue participating through alternative mechanics, such as the ghost system in the maze concept

## Reflection

Overall, this work helped me better understand the relationship between **multiplayer design, player count, connectivity, and technical limitations**.

Instead of designing a game around a fixed number of players, I am exploring how the game itself can adapt to the crowd. The unpredictable nature of a large multiplayer environment can become an important part of the experience rather than something that needs to be completely controlled.

A key design principle that came out of this process is:

> **The game should adapt to the crowd rather than requiring the crowd to adapt to the game. ****

## Next Steps

Next, I will compare the four concepts more closely and determine which idea best fits the large-crowd exhibition environment. I need to consider which concept best balances **fun gameplay, accessibility, connectivity, and technical feasibility**.



# Game Development Log & Reflection Journal

**Project:** Gameplay Prototypes for Client Demonstration  
**Prototypes:** 2D Arcade Soccer & Infinite Tower Physics  
**Engine & Tooling:** Unity 6 (6000.3.5f1 LTS) | C# Scripting | Unity 2D Physics Engine  
**Role:** Gameplay Programmer & Designer  
**Purpose:** Explore and demonstrate potential gameplay mechanics to teammates in preparation for a client presentation.

## 1. Project Overview & Objectives

During this development session, I created two gameplay prototypes to explore potential directions for our team's large-crowd multiplayer game project. The objective was to build small, functional demonstrations of different gameplay ideas to present to my teammates. These prototypes would help us evaluate mechanics, discuss feasibility, and decide which concepts were worth presenting to our client.

The prototype explored a top-down, 2D arcade soccer game featuring player movement, ball possession, shooting, bouncing physics, and an AI-controlled goalkeeper. The second prototype explored an infinite vertical tower game featuring procedural platform generation, block pickup and throwing, and physics-based platform placement.

Rather than developing two complete games, I focused on implementing their core interactions so that my teammates could experience the gameplay ideas directly instead of relying exclusively on verbal explanations or written concepts. Building these prototypes also let me explore technical challenges for each idea, including collision handling, physics stability, procedural generation, and responsive player controls.

The prototypes served as exploratory tools for our team's design process. By making the mechanics playable, I could demonstrate how different gameplay systems might work in practice and provide a stronger foundation for discussing potential directions with our client.

## 2. Prototype Development & Technical Exploration

### A. 2D Arcade Soccer Prototype

The arcade soccer prototype explored a fast-paced, physics-driven multiplayer experience. I implemented player movement, automatic ball possession, impulse-based shooting, high-bounciness collisions, and a predictive goalkeeper AI.

The ball attaches to the player through a designated `BallHoldPosition` object and switches between a possession state and an independent physics state when kicked. Pressing Space launches the ball based on the player's movement or facing direction. I also configured physics materials to create energetic rebounds off the arena boundaries and developed a goalkeeper that predicts where the ball will intersect the goal line.

These mechanics allowed me to demonstrate the basic feel of controlling a player, shooting a ball, and interacting with an environment governed by arcade-style physics. The prototype also helped me identify technical considerations that could affect gameplay, such as maintaining responsive controls, preventing high-speed collision issues, and keeping the goalkeeper stable during impacts.

### B. Infinite Tower Physics Prototype

The infinite tower prototype explored a different gameplay direction centred on vertical movement, object manipulation, and physics-based construction. I implemented a procedural platform generator that creates new platforms as the player progresses upward. In contrast, the player can pick up nearby blocks, carry them, and throw or place them within the environment. I also developed collision checks to ensure that blocks lock into place when landing on platform surfaces rather than attaching incorrectly to their sides.

This prototype let me demonstrate how players might interact with a continuously expanding environment and manipulate physical objects as part of gameplay. It also revealed technical challenges related to procedural ground object overlap, stable platform collisions, and predictable throwing mechanics.

## 3. Reflection: Prototyping for Team Collaboration

The main value of these prototypes was not producing finished products, but giving my team something tangible to evaluate as we explored gameplay possibilities for our client project. By implementing the core mechanics, I could communicate ideas through playable examples and help the team move from abstract concepts toward practical demonstrations.

Developing the prototypes also helped me investigate the technical feasibility of different mechanics before committing to a particular direction. For example, the soccer prototype required me to manage ball possession, collision behaviour, and goalkeeper movement. In contrast, the tower prototype required me to solve problems involving procedural generation, object manipulation, and platform stability. Working through these challenges gave me useful insight into the implementation effort and potential limitations of each concept.

Another important aspect of this work was supporting team discussion and preparation for the client demonstration. The prototypes could serve as starting points for evaluating which mechanics were most interesting, technically achievable, and adaptable to the project's broader goals.

Overall, this process reinforced the value of rapid prototyping during game design. A prototype doesn't need to include every planned feature to be useful. By focusing on a small set of representative mechanics, I could create demonstrations that helped my teammates visualize and discuss alternatives and make more informed decisions about the project's direction.

## 4. Next Steps

- [ ] Present prototypes to my team and gather feedback on the mechanics.
- [ ] Identify which elements best support the team's overall game concept and client requirements.
- [ ] Discuss the strengths, limitations, and technical feasibility of each gameplay direction, producing findings based on team feedback.
- [ ] Prepare a focused demonstration for the client that communicates the selected gameplay ideas clearly.

## 5. Conclusion

These two prototypes were developed as exploratory gameplay demonstrations to support team collaboration and preparation for a client presentation. The arcade soccer prototype investigated fast-paced movement and physics-driven ball interactions, while the infinite tower prototype explored procedural generation, object manipulation, and platform-based gameplay.

By building functional examples of these mechanics, I was able to provide the team with concrete material to evaluate potential game concepts. The process also helped me identify technical challenges early and better understand what it takes to implement different gameplay systems. Ultimately, the prototyping and discussion helped us determine which gameplay directions were worth exploring further with our client.


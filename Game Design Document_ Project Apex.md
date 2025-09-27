# Game Design Document: Project Apex

**Author**: Manus AI
**Date**: September 27, 2025
**Version**: 1.0

## 1. Introduction

### 1.1. Game Title
Project Apex

### 1.2. Genre
Open-world Racing, Action, Arcade

### 1.3. Target Audience
Players aged 12+ who enjoy high-speed street racing, car customization, and intense police pursuits. Fans of the Need for Speed series, particularly *Most Wanted (2005)*, will find familiar and enhanced gameplay elements.

### 1.4. Platform
Initial release on Windows PC, with future considerations for Android and iOS mobile platforms.

### 1.5. Unique Selling Proposition (USP)
Project Apex combines the thrilling open-world street racing and deep car customization of classic arcade racers with an engaging narrative-driven career mode centered around an escalating rivalry with an elite group of street racers and relentless police pursuits. The game will feature dynamic weather, a robust reputation system, and highly interactive environments to create a truly immersive and replayable experience.

### 1.6. Inspiration
This game is heavily inspired by **Need for Speed: Most Wanted (2005)**, aiming to capture its essence of illegal street racing, iconic police chases, and a compelling progression system, while modernizing it with contemporary graphics (Unity 6 URP) and refined gameplay mechanics.

## 2. Gameplay

### 2.1. Core Gameplay Loop
The core gameplay loop revolves around **open-world exploration**, participating in **street races** to earn money and reputation, **customizing vehicles** for both performance and aesthetics, and engaging in **high-stakes police pursuits**. Success in these activities contributes to challenging and defeating the **Blacklist** racers, ultimately progressing through the game's narrative.

### 2.2. Game Modes

#### 2.2.1. Career Mode
This is the primary single-player experience, featuring a story-driven progression where the player rises through the ranks of the street racing scene to challenge and defeat the 

Blacklist, a group of the city's most notorious racers.

#### 2.2.2. Quick Race
Allows players to set up custom races with any unlocked car and track. This mode is for players who want to jump straight into the action without the narrative context of Career Mode.

#### 2.2.3. Challenge Series
A series of 70+ unique events that test the player's driving skills in various scenarios, such as time trials, pursuit milestones, and specialized challenges.

### 2.3. The Blacklist: Progression System
The Blacklist is a list of 15 elite street racers who dominate the city's racing scene. The player's primary objective is to defeat each member of the Blacklist in a one-on-one race to become the most notorious racer in the city.

To challenge a Blacklist member, the player must meet a set of requirements:

*   **Race Wins**: Win a specific number of races.
*   **Milestones**: Complete specific pursuit-related objectives (e.g., evade police in a certain time, cause a certain amount of cost to state).
*   **Bounty**: Accumulate a target amount of bounty from police pursuits.

Defeating a Blacklist member rewards the player with a significant cash prize and the opportunity to win their opponent's car (pink slip) or unique performance and visual customization parts.

### 2.4. Race Events
Project Apex will feature a variety of race event types to keep the gameplay fresh and exciting:

| Event Type      | Description                                                                                             | 
| --------------- | ------------------------------------------------------------------------------------------------------- | 
| **Circuit**     | Standard lap-based races against multiple opponents.                                                    | 
| **Sprint**      | Point-to-point races from one location to another.                                                      | 
| **Drag**        | Short, straight-line races focused on perfect shifting and acceleration.                                | 
| **Lap Knockout**| A multi-lap race where the last-place driver is eliminated at the end of each lap until one winner remains. | 
| **Speedtrap**   | A point-to-point race where the winner is determined by the highest cumulative speed recorded at various checkpoints. | 
| **Tollbooth**   | A time-trial race where the player must reach a series of checkpoints before time runs out.             | 

### 2.5. Police Pursuit System
The police are a constant threat in Project Apex, and their presence adds a layer of risk and excitement to the gameplay. The police system is designed to be dynamic and challenging, with escalating difficulty based on the player's actions.

#### 2.5.1. Heat Levels
The **Heat Level** represents the player's wanted status. There are 5 standard heat levels, with a 6th level reserved for special high-stakes pursuit events. As the heat level increases, the police become more aggressive, deploy more advanced tactics, and use more powerful vehicles.

| Heat Level | Police Response                                                                                                                              | 
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------- | 
| 1          | Local police units in standard cruisers. Basic pursuit tactics.                                                                              | 
| 2          | Introduction of roadblocks and more aggressive pursuit tactics.                                                                              | 
| 3          | State police join the chase with faster cars and more advanced tactics like PIT maneuvers. Light SUVs may also be deployed.                      | 
| 4          | Undercover police units and heavy SUVs join the pursuit. Spike strips are deployed at roadblocks.                                            | 
| 5          | Federal authorities take over the pursuit with high-performance vehicles and helicopters. A special, highly skilled officer will lead the chase. | 

#### 2.5.2. Pursuit Breakers
The city is filled with **Pursuit Breakers**, which are large, destructible objects in the environment (e.g., water towers, gas stations, large signs). Triggering a Pursuit Breaker at the right time can create a massive obstacle for pursuing police vehicles, allowing the player to escape.

#### 2.5.3. Cooldown and Evasion
To escape a pursuit, the player must break the line of sight with all pursuing police units. Once out of sight, a **Cooldown** meter will appear. The player must remain hidden until the meter fills to successfully evade the police. Hiding spots scattered throughout the city will accelerate the cooldown process.

## 3. Car Customization

### 3.1. Performance Customization
Players can upgrade their vehicles with a wide range of performance parts, including engine, transmission, suspension, tires, and nitrous. Unique “Junkman” parts, won from Blacklist members, offer superior performance enhancements.

### 3.2. Visual Customization
Players can visually customize their cars to a high degree of detail, including:

*   **Body Kits**: Spoilers, hoods, bumpers, and side skirts.
*   **Paint and Vinyls**: A wide selection of colors, finishes, and vinyl designs.
*   **Rims and Tires**: A variety of rim styles and tire options.
*   **Window Tint**: Various shades of window tint.

Visual customization not only allows for personal expression but also serves a gameplay purpose by reducing a car's heat level.

## 4. World Design

### 4.1. The City of Rockport
The game is set in the fictional city of Rockport, a diverse open world with distinct districts, including a dense urban core, industrial areas, and scenic rural outskirts. The city is designed to be a playground for high-speed racing and intense pursuits, with a network of highways, back alleys, and off-road shortcuts.

### 4.2. Dynamic Environment
The world will feature a day-night cycle and dynamic weather, including rain, which will affect road conditions and car handling. The environment is also highly interactive, with destructible objects and the aforementioned Pursuit Breakers.

## 5. Technical Details

*   **Game Engine**: Unity 6
*   **Render Pipeline**: Universal Render Pipeline (URP)
*   **Target Platform**: Windows PC



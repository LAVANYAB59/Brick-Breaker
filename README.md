🧱 Brick Breaker Game

A simple Brick Breaker arcade game developed using Java. The game follows a modular 

project structure and demonstrates object-oriented programming concepts, game loop handling, and separation of 

concerns using service and bean layers.

🎮 Game Overview

Brick Breaker is a classic arcade game where the player controls a paddle to bounce a ball and 

break bricks. The objective is to destroy all bricks without letting the ball fall below the paddle.

📁 Project Structure

BrickBreaker
│

├── src

│   ├── com.kce.brick.bean

│   │   └── Game.java

│   │

│   ├── com.kce.brick.main

│   │   └── GameMain.java

│   │

│   ├── com.kce.brick.service

│   │   └── GameService.java

│   │

│   └── module-info.java

Package Description

com.kce.brick.bean

Contains the core game data models.

Game.java represents the main game object and state.

com.kce.brick.main

Entry point of the application.

GameMain.java starts and initializes the game.

com.kce.brick.service

Contains game logic and services.

GameService.java manages gameplay operations and rules.

module-info.java

Defines the Java module configuration for the project.

⚙️ Technologies Used

Java

Object-Oriented Programming

Java Modules

GameMain.java

🎯 Features

Paddle movement control

Ball collision detection

Brick destruction mechanics

Score tracking

Modular code structure

🚀 Future Improvements

Add sound effects

Multiple levels

High score system

Pause and restart functionality

Enhanced graphics

👨‍💻 Author

Developed as a Java project to demonstrate basic game development and modular programming concepts.

Output:

<img width="945" height="787" alt="image" src="https://github.com/user-attachments/assets/abe9ba8a-0817-4066-a242-387ec6f91714" />

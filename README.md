# Projet JacoBhashi

<div align="center">
  <img src="https://github.com/RyuAragi/Projet-HASHI/assets/44385130/40ee9446-c68d-4362-81a9-e33b3670330e" alt="Logo du Projet" width="200">
</div>

[![Pull Requests](https://img.shields.io/github/issues-pr/RyuAragi/Projet-HASHI.svg?style=flat-square)](https://github.com/RyuAragi/Projet-HASHI/pulls)
[![Commits](https://img.shields.io/github/commits-since/RyuAragi/Projet-HASHI/latest.svg?style=flat-square)](https://github.com/RyuAragi/Projet-HASHI/commits/main)
[![Version](https://img.shields.io/github/v/tag/RyuAragi/Projet-HASHI.svg?style=flat-square&labelColor=green)](https://github.com/RyuAragi/Projet-HASHI/releases/latest)
[![Release](https://img.shields.io/github/release/RyuAragi/Projet-HASHI.svg?style=flat-square)](https://github.com/RyuAragi/Projet-HASHI/releases/latest)

## Introduction

JacoBhashi is a desktop application for the popular logic puzzle game Hashiwokakero (also known as Bridges). Developed in JavaFX with Spring Boot and Maven, this project provides a feature-rich and engaging puzzle-solving experience. It was created as part of a university software engineering course.

## Table of Contents
- [About The Game](#about-the-game)
- [Features](#features)
- [Get Started](#getting-started)
- [How to Play](#how-to-play)
- [Project Members](#project-members)

## About The Game

Hashiwokakero is a logic puzzle where the objective is to connect a series of islands with bridges. The number on each island indicates the exact number of bridges that must be connected to it. The puzzle is solved when all islands are connected into a single, continuous network.

This implementation, JacoBhashi, brings the classic puzzle to your desktop with a modern interface and several helpful features designed for both new and experienced players.

## Features

- **Multiple Game Modes**:
  - **Classic Mode**: Play with standard Hashi rules. 
  - **Breaking Bridges Mode**: A challenging mode where incorrectly placed or timed bridges will break after a certain period.
- **Variety of Levels**: Puzzles are available in multiple difficulties (Easy, Medium, Hard), each with a wide selection of grids.
- **Interactive Gameplay**: A user-friendly interface for building and removing bridges with simple mouse clicks.
- **Undo/Redo**: Easily take back or re-apply your moves.
- **Hypothesis Mode**: Safely test out potential bridge placements without affecting your main solution.
- **Solution Checker**: Verify your current grid setup and get feedback on incorrect bridges.
- **In-Game Help System**: Get hints when you're stuck. The system can highlight areas of interest or suggest specific solving techniques.
- **Tutorials**: A dedicated section to learn the rules and various solving techniques, from beginner to advanced.
- **Persistent Saves**: The game automatically saves your progress for each level under your user profile, allowing you to resume anytime.
- **Leaderboards**: Compete for the best scores and completion times on each level.
- **Customizable Settings**: Adjust sound and music volume to your liking.

## Getting Started

To run the game on your local machine, follow these steps.

### Prerequisites

- **Java Development Kit (JDK) 21**: Ensure you have JDK 21 installed.
- **Apache Maven**: The project is built using Maven.

### Installation & Launch

1. Clone the repository:
```bash
git clone https://github.com/theoduluard/Projet-HASHI.git
```

2. Navigate to the project directory:
```bash
cd Projet-HASHI
```

3. Run the application using Maven:
```bash
mvn spring-boot:run
```

This command will compile the source code, resolve dependencies, and launch the JavaFX application.

## How to Play

### Main Objective

The goal is to connect all islands to form a single connected group, ensuring that the number of bridges connected to each island matches the number displayed on it.

### Rules

- Bridges must begin and end on distinct islands.
- Bridges must be horizontal or vertical and cannot cross other bridges or islands.
- There can be at most two bridges between any two islands.
- All islands must be interconnected.

### Controls

- **Enter Username**: Before starting, enter a username on the main menu. This enables game saving and leaderboard tracking.
- **Building Bridges**: In the game, hover your mouse over an island. Potential bridge paths to neighboring islands will appear.
  - **Click** on a highlighted path to build a single bridge.
  - **Click** again on a single bridge to build a double bridge.
  - **Click** a third time to remove the bridges.
- **In-Game Buttons**:
  - **Home**: Quit the current game and return to the main menu. Your progress will be saved.
  - **Settings (Cog icon)**: Open the in-game settings menu to adjust sound or start a new game.
  - **Restart**: Resets the current grid to its initial state.
  - **Undo/Redo**: Step backward or forward through your moves.
  - **Help (?)**: Request a hint from the game's help system.
  - **Check (✓)**: Verify your solution and highlight any incorrect bridges.
  - **Hypothesis**: Toggle hypothesis mode to try out moves without commitment. In this mode, you can validate or discard your hypothetical bridges.
  - **Zoom In/Out**: Adjust the size of the game grid for better visibility.

## Project members

- [@KirZaping](https://github.com/KirZaping) - Wandrille BALLEREAU
- [@Theo-dlrd](https://github.com/Theo-dlrd) - Théo Duluard
- [@thibcour](https://github.com/thibcour) - Thibault Courcol
- [@Medvil03](https://github.com/Medvil03) - Rémy Georget
- [@XavierCoupe](https://github.com/XavierCoupe) - Xavier Coupe
- [@sedraalhallak](https://github.com/sedraalhallak) - Sedra Alhallak
- [@ElGhoumari](https://github.com/ElGhoumari) - Soumia ElGhoumari
- [@RyuAragi](https://github.com/RyuAragi) - Victor Fouqueray

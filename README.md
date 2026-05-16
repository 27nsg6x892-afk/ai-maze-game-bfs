# Maze Game with BFS Path Finding

## Overview

This project is a 2D maze game built with Python and Pygame. The player starts from a main menu, enters a difficulty level, and the program generates a random maze. The project uses Breadth-First Search (BFS) to find and display a path between the start point and the end point.

The project demonstrates basic artificial intelligence search concepts, game development, random maze generation, user input handling, and visual path finding.

## Objectives

- Build an interactive maze game using Python and Pygame
- Allow the user to enter a difficulty level
- Generate a random 10 x 10 maze
- Use BFS to search for a path from the start cell to the end cell
- Display the maze visually using different colors
- Add menu navigation and basic audio controls

## Features

- Main menu screen
- Difficulty input screen
- Random maze generation
- BFS path finding
- Visual path drawing
- Colored cells for walls, open cells, start, end, and path
- Volume up, volume down, and mute options
- Reusable button class

## How It Works

1. The user opens the game.
2. The main menu appears.
3. The user enters a difficulty level from 1 to 100.
4. The program generates a random 10 x 10 maze.
5. The difficulty value controls the probability of walls.
6. BFS searches for a route between the start and end points.
7. If a path is found, the path is displayed visually on the maze.

## Algorithm Used

### Breadth-First Search

BFS is used to explore the maze grid and find a path from the start cell to the end cell. It checks neighboring cells in four directions and uses a parent dictionary to trace the discovered path back after reaching the end point.

BFS is suitable for this project because the maze is an unweighted grid, and BFS can find the shortest path in terms of number of steps.

## Project Details

- Maze size: 10 x 10
- Total cells: 100
- Difficulty range: 1 to 100
- Wall probability: difficulty / 100
- Cell size: 60 pixels
- Main screen size: 1678 x 944 pixels
- Volume step: 0.1
- Transition delay: 300 ms

## Cell Colors

- Wall: dark gray
- Open cell: light gray
- Start cell: green
- End cell: red
- BFS path: cyan

## Source Files

- `main.py` - Handles the game loop, screens, input handling, drawing, and audio options
- `maze.py` - Contains maze generation logic and BFS path-finding algorithm
- `button.py` - Defines a reusable button class for menu screens
- `Maze_Game_Project_Report_English.pdf` - Project report
- `requirements.txt` - Required Python package

## Tools & Technologies

- Python
- Pygame
- Breadth-First Search
- Random maze generation

## Repository Structure

- main.py
- maze.py
- button.py
- Maze_Game_Project_Report_English.pdf
- requirements.txt
- README.md
- assets/

## How to Run

1. Clone the repository:

`git clone https://github.com/27nsg6x892-afk/maze-game-bfs-pathfinding.git`

2. Install the required package:

`pip install -r requirements.txt`

3. Run the game:

`python main.py`

## Notes

- Some assets such as images, fonts, or audio files may be required depending on the local version of the project.
- If assets are not included, update the file paths or add the missing assets before running the game.
- Very high difficulty values may generate mazes with no valid path.

## Project Status

Completed as an academic Intro to AI project.

## Author

Mark Samy Sabry

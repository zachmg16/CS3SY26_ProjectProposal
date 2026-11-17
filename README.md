# CS3SY26_ProjectProposal by AlMendiza

## Project Proposal Template

### Project Title or Name of the Application	: Lessons in Logic through Minesweeper
### Section			   	      : 9-Magnesium
### Group Members			    : Bercasio, Matubis, San Agustin
### Date (Proposal Date)  : November 17, 2026

### Project Description:

This program simulates the simple game known as Minesweeper, and uses it to help teach the user lessons in basic logic and reasoning. Minesweeper is a game where you have a grid of tiles and each tile can either be safe or a mine. At the start of the game, all tiles are hidden until you click to reveal a tile. If a tile has a number on it, that number shows the amount of mines in the area surrounding it. You win by revealing all the safe tiles, and you lose by clicking on a mine. While the game seems simple at first, it is actually quite cognitively demanding. Skills like pattern recognition, deduction, and reasoning are regularly used if not required to solve a board. This program can help teach or enhance these skills while still being fun and engaging for the user.

Needed libraries to import for this project are tkinter, as we plan on making the game interactable in a separate window with mouse inputs, and random, in order to randomize the layout of mines for each board. Some features we ideally plan on adding alongside the basic game of Minesweeper are difficulty options (eg. easy, medium, and hard modes, where each mode has a different sized board with less or more mines depending on the option), and an optional "tutorials" button where we will teach the user how to play, while integrating our lessons in logic. 

Our target demographics for this project are students interested in learning logic and reasoning, people interested in minesweeper, and minesweeper players who want to learn how they can apply their skills in different situations.

We have proposed and designed a program with a modular game design, running along a Game controller that manages the overall loop of the game. Naturally, games do not shine without their essential parts in play, so it is linked to a Board and multiple Tile objects that can change states along with their attributes and methods. To go along with this, built-in methods such as "get_neighbors()" or "calculate_surrounding_mine()" handle many queries involving data analysis for adjacent coordinates on the graph. This is how the game runs on its modular code, but going into the script itself provides customizable parameters and logic tiles to assist the user. Of course, Minesweeper isn't the only focus of this project, as aside from helping players work out their logical and analytical skill in a set-up space, the whole thing could work as a simulation for real-life situations. Examples to provide a sense of what we propose can be Epidemiology and Disease Outbreak Tracking, where researchers for public health grid out local testing results to find the most effective outbreak sources while minimizing widespread exposure, or Robotics and Navigation, where drones use grids in their script to map unknown terrain and detect obstacle after obstacle in sectors to chart a safe path to their destination.

**Sample class Diagram from https://static.visual-paradigm.com/web/images/tutorials/class-diagram-tutorial/01-class-diagram-example.png:**

![Sample Diagram](https://static.visual-paradigm.com/web/images/tutorials/class-diagram-tutorial/01-class-diagram-example.png)

### Goals:

For our goals, we plan to put deductive thinking into gameplay, and leveraging players to use their skills in-game for problem-solving in actual real-world situations. With the more understandable language of Minesweeper, we will translate the difficult process of logical reasoning for the players. Even throughout the base code of the game, spatial awareness under pressure challenges players to navigate the grid-based minefield with the utmost care, utilizing their spatial visualization and composure, lest their whole game explodes to bits. With the implemented pressure into the mix, we would also like to expose and prepare players for problems that—much like the real world—are not so merciful with time. Being aware of everything is a vital skill that we are trying to train players. Lastly, we would like to delve into the promotion of experiential learning and interactive science with hands-on logic to everyday decision-making. Obviously, such plays could not have been made without the usage of practical scientific and mathematical principles, so the simulation as a whole aims to not only strengthen players' skill but to hone their love for the "language of the universe." With the gamification of the simple script, players can wholly transform logical concepts into graspable and applicable principles that they can apply outside the simulation.

- Objective 1: to integrate the usage of logical and analytical thinking (that can be applied and used in real world situations) into the minds of the players within the confines of the simulation
- Objective 2: to help players deal with high-stakes pressure better and strengthen their spatial awareness within the given limitations
- Objective 3: to make players handle situations first-hand that could not only help them apply logical thinking to basic day-to-day life, but also strengthen support for interactive science
- Objective 4: to make logical thinking be easier to remember and apply in real life to players by making it in the form of an interactive game, which helps the minds of players understand it better

[Click here for Rubrics and Sample projects](https://docs.google.com/document/d/1xKd1CqK6DcNWS2_oJPBNtY5n3I3Hqiw8FY3W295Iqfk/edit?usp=sharing)

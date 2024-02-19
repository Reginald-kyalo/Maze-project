# Maze-project

The Maze is 3D game built using SDL2 and Raycasting. The player can move in all four directions using keys ```W```, ```A```, ```S```, and ```D```. 

The player can move through the maze and turn left or right as desired.

If the player hits a wall, they cannot move unless they change their direction.

The player can move on several directions and rotate in the same time.

## Installation

Clone this repo:
```bash
git clone https://github.com/Reginald-kyalo/Maze-project.git
```
## Compiling
This project makes use of gcc and make for the compilation process.

### Windows
Ensure you have gcc, and make(Can install using chocolatey). Then run the following command:

```bash 
make
```
### Linux
First make sure SDL is installed. If you haven't install SDL by running ``` make linux_install ```. Then run the following command:

```bash
make linux 
```
to compile.

### Mac
Ensure sdl is installed. Then run the following command:

```bash
make mac
```
## Running
After successfully compiling run the program using following command:

```bash
./maze MAP
```

where ```MAP``` is the name of the file found in the maps folder. You can create other maps and pass them while running program as above. Map files accept only the allowed characters.

## Controls

```W``` - Moving forward

```S``` - Moving backward

```A``` - Look left

```D``` - Look right

```Mouse move left/right``` - look left or right

```M``` - Turn off map visibility. The 2D map won't be visible on clicking

```N``` - Turn on map visibility. The 2D map will be visible again if it wasn't

***Have fun!***
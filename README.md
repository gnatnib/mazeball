# Maze Ball

<img src="https://upload.wikimedia.org/wikipedia/commons/1/18/ISO_C%2B%2B_Logo.svg" alt="C++ Logo" width="100" height="100">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/0a/OpenGL_Logo.svg" alt="OpenGL Logo" width="100" height="100">

This is an OpenGL-based maze game written in C++, where the player navigates a sphere through a maze using keyboard controls. The project uses the GLUT library for windowing and input management.

## Features

- 3D maze rendered with OpenGL.
- Keyboard controls to move the sphere.
- Adjustable camera and acceleration settings.
- Realistic physics with friction and collision detection.

## Controls

- **Arrow Keys**: Move the sphere.
- **Q/W**: Zoom out/in the camera.
- **E/R**: Decrease/increase acceleration.

## Installation

To compile and run the project, you need to have OpenGL and GLUT installed on your system.

### On Linux

1. Install the necessary libraries:
    ```sh
    sudo apt-get update
    sudo apt-get install freeglut3 freeglut3-dev
    ```

2. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/maze-game.git
    cd maze-game
    ```

3. Compile the code:
    ```sh
    gcc -o maze_game maze_game.c -lGL -lGLU -lglut -lm
    ```

4. Run the game:
    ```sh
    ./maze_game
    ```

### On Windows

1. Install [MinGW](http://www.mingw.org/) and add it to your PATH.
2. Install [FreeGLUT](http://freeglut.sourceforge.net/).
3. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/maze-game.git
    cd maze-game
    ```
4. Compile the code:
    ```sh
    gcc -o maze_game maze_game.c -lfreeglut -lopengl32 -lglu32 -lm
    ```
5. Run the game:
    ```sh
    maze_game.exe
    ```

### On macOS

1. Install the necessary libraries using Homebrew:
    ```sh
    brew install freeglut
    ```

2. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/maze-game.git
    cd maze-game
    ```

3. Compile the code:
    ```sh
    gcc -o maze_game maze_game.c -framework OpenGL -framework GLUT -lm
    ```

4. Run the game:
    ```sh
    ./maze_game
    ```

## Code Overview

- **maze_game.c**: The main game file containing all the OpenGL initialization and game logic.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This project uses [GLUT](https://www.opengl.org/resources/libraries/glut/) for window management and input handling.
- Maze generation inspired by classic maze games and tutorials.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.

## Contact

For any inquiries or issues, please contact `your.email@example.com`.

# Maze Ball

<img src="https://upload.wikimedia.org/wikipedia/commons/1/18/ISO_C%2B%2B_Logo.svg" alt="C++ Logo" width="50" height="50">

This is an OpenGL-based maze game written in C++, where the player navigates a sphere through a maze using keyboard controls. The project uses the GLUT library for windowing and input management.

## Demo
![mazeBall](https://github.com/gnatnib/mazeball/assets/117698972/dfa62844-1dae-4e50-8a4c-78cf47115683)

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
    git clone https://github.com/gnatnib/mazeball.git
    cd mazeball
    ```

3. Compile the code:
    ```sh
    gcc -o mazeball main.cpp -lGL -lGLU -lglut -lm
    ```

4. Run the game:
    ```sh
    ./mazeball
    ```

### On Windows

1. Install [MinGW](http://www.mingw.org/) and add it to your PATH.
2. Install [FreeGLUT](http://freeglut.sourceforge.net/).
3. Clone this repository:
    ```sh
    git clone https://github.com/gnatnib/mazeball.git
    cd mazeball
    ```
4. Compile the code:
    ```sh
    gcc -o mazeball main.cpp -lfreeglut -lopengl32 -lglu32 -lm
    ```
5. Run the game:
    ```sh
    main.cpp
    ```

### On macOS

1. Install the necessary libraries using Homebrew:
    ```sh
    brew install freeglut
    ```

2. Clone this repository:
    ```sh
    git clone https://github.com/gnatnib/mazeball.git
    cd mazeball
    ```

3. Compile the code:
    ```sh
    gcc -o mazeball main.cpp -framework OpenGL -framework GLUT -lm
    ```

4. Run the game:
    ```sh
    ./mazeball
    ```

## Code Overview

- **main.cpp**: The main game file containing all the OpenGL initialization and game logic.

## Acknowledgements

- This project uses [GLUT](https://www.opengl.org/resources/libraries/glut/) for window management and input handling.
- Maze generation inspired by classic maze games and tutorials.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.

## Contact

For any inquiries or issues, please contact `bintang.syafrian@gmail.com`.

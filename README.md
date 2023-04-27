
# PacMan Factory 🕹️

This project is a simple web-based game that demonstrates various JavaScript concepts, including DOM manipulation, event handling, animations, and collision detection. The game allows the user to create multiple Pac-Man instances that move around the screen, changing their images as they move, and bouncing off the edges of the screen.

## Table of Contents
1. [Concepts](#concepts)
2. [How It Works](#how-it-works)
3. [Run Locally](#run-locally)
4. [Roadmap](#roadmap)
5. [License](#license)
## Concepts

- **DOM Manipulation:** The code uses getElementById and createElement to interact with the HTML DOM, creating Pac-Man instances and appending them to the game container.
- **Event Handling:** The toggleGame function is attached to a button click event, allowing the user to pause and resume the game.
- **Animations:** The update function is responsible for moving the Pac-Man instances and updating their positions on the screen. The setTimeout function is used to call update periodically, creating a smooth animation.
- **Collision Detection:** The checkCollisions function checks if a Pac-Man instance has collided with the edges of the screen and reverses its velocity accordingly.
- **Arrays and Loops:** The pacMen array stores all the created Pac-Man instances, and the forEach loop is used to iterate over them and update their positions and images.


## How It Works
- **pacArray** contains the file names of the Pac-Man images that will be used to create the animation effect.

- **pacMen** is an array that stores all the created Pac-Man instances.

- **gameRunning** is a boolean variable that determines whether the game is running or paused.

- **setToRandom(scale):** Generates an object with random x and y coordinates, both multiplied by the given scale.

- **makePac():** Creates a new Pac-Man instance with random position and velocity, appends it to the game container, and returns an object containing its position, velocity, image element, and frame counter.

- **update():** Called periodically to update the position of each Pac-Man instance, check for collisions, and update their images based on their direction and frame counter.

- **checkCollisions(item):** Checks if a Pac-Man instance has collided with the edges of the screen and reverses its velocity accordingly.

- **makeOne():** Creates and adds a new Pac-Man instance to the pacMen array.

- **toggleGame():** Toggles the game state between running and paused, and updates the "Stop Game" button text accordingly.

The game starts when the user clicks the "Start Game" button, which triggers the update function. The user can create new Pac-Man instances by clicking the "Add PacMan" button, and pause or resume the game using the "Stop Game" button.

## Run Locally

Click on the green Code button and download the zip file. Click on the index.html file and view the interactive application in your browser.

## Roadmap

- Change the pacman to a pug. Add a button that randomly generates images of food. When the pugmen eat a piece of food they will leave a poo emoji behind them. 


## License

[MIT](https://choosealicense.com/licenses/mit/)


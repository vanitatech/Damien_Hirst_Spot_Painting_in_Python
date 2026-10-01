# Damien Hirst Spot Painting

A Python Turtle graphics project that recreates the style of Damien Hirst's colourful spot paintings using randomly selected colours.

## Project Overview

This project uses Python's `turtle` module to create a grid of 100 coloured dots.

Each dot is randomly selected from a predefined colour palette extracted from a reference image. The Turtle moves across the screen, creating a new row after every 10 dots.

## Technologies

* Python
* Turtle Graphics
* Random module

## Features

* Creates a 10 × 10 grid of coloured dots
* Randomly selects colours for each dot
* Uses RGB colour values
* Automatically moves to a new row after every 10 dots
* Uses Turtle graphics to generate the artwork

## How It Works

The program:

1. Creates a Turtle object and hides the Turtle cursor.
2. Sets the screen colour mode to RGB.
3. Stores a palette of RGB colours.
4. Randomly selects a colour for each dot.
5. Draws 100 dots using a loop.
6. Moves to the next row after every 10 dots.
7. Keeps the window open until the user clicks.

## What I Learned

* Using Python's `turtle` module
* Working with RGB colours
* Using `random.choice()`
* Using `for` loops
* Using the modulo operator `%` to detect every 10th iteration
* Controlling Turtle movement and direction
* Creating patterns using loops and coordinates

## Run the Project

Clone the repository and run:

```bash
python main.py
```

A Turtle graphics window will open and generate the artwork.

## Future Improvements

* Extract colours automatically from an image using `colorgram`
* Allow the user to choose the number of rows and columns
* Allow different dot sizes
* Add a user-selected colour palette

---

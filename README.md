# Tetris

In this assignment, you will implement the core functionality for a game of Tetris.

The project has two implementation files:
- core.py
- gui.py

and one test file:
- core_test.py


# Objective 1
## Implementing the Grid class

Inside the core.py, there is a Grid class.
Some of Grid's methods have the following line for their body:

    raise NotImplementedError("Replace this line with your implementation")

Your job is to replace these lines with a satisfactory implementation of that method.
You can use core_test.py to test your implementation.

After implementing these methods, you should be able to play the game!

# Objective 2
## Adding new blocks

Inside core.py there is a function new_block.
It returns a random Block from a list of Blocks.
Spice up your implementation of Tetris by adding new Blocks.

# Objective 3
## Giving Blocks Color

Change the code in gui.py so that blocks are colored randomly each frame.

# Objective 4
## Speeding Up

Change the code in gui.py so that the game speeds up over time instead of using a constant tick rate.

# Objective 5
## Keeping Score

Change the code in gui.py to maintain and display users score.
You can decide how the game is scored and how the score should be displayed.

# Before You Begin

    $ python3 -m pip install pytest

# To Test

    $ py.test

# To Play

    $ python3 gui.py
# Tetris

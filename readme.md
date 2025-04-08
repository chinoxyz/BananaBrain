


# Solving Banana Brain environment with Deep Reinforcement Learning
The instructions of the problem are described in https://github.com/udacity/Value-based-methods#dependencies

The goal is to solve the problem in less than 1800 episodes. 

## Environment Description

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. 
The simulation contains a single agent that navigates a large environment. 
At each time step, it has four actions at its disposal:

    0 - walk forward
    1 - walk backward
    2 - turn left
    3 - turn right

The problem is considered solved when we collect an average reward of 13 in the last 100 episodes.

## Installation

The requirements of the project were updated to use python 3.12 and latest libraries.
A new list of requirements was provided and to install them we need an virtual environment.
Do ```pip install .``` to install them.

For the environment download:
Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip
Windows (64-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip


## How to reproduce the results?

The Environment was solved in 439 episodes! For more information about the result check the report.md.

To reproduce the results run Navigation.ipynb with jupyter lab.
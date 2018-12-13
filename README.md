# Project 1: Navigation

## Project Details

This project uses a modified version of the "Banana Collector" Unity ML Agent environment. The environment contains yellow and blue bananas, which provide a +1 and -1 reward when "collected."

The state space is 37 dimensional, which includes the agent's velocity, as well as information about bananas along lines of sights from the agent's perspective.

The action space is 4 dimensional:

* 0 - move forward
* 1 - move backward
* 2 - turn left
* 3 - turn right

## Getting Started

1. Follow [Udacity's instructions for installing dependencies](https://github.com/udacity/deep-reinforcement-learning#dependencies).

2. Download the Banana environment by following the link appropriate for your platform:

Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

Then, unzip the file into root of this repository.

## Instructions

Run 'jupyter notebook' in the repo directory, and run the Navigation_training.ipynb notebook to train the agent.


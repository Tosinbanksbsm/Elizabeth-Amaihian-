# Elizabeth-Amaihian-

Elizabeth Amaihian Moving Bird Final Edit 1
# Moving Bird



A simulation for an automated Bird in Unity Development. This project implements a simple-reflex agent in this environment.


 

# Performance measure 
- How much energy is used

 
 1. Support for training single-agent, via several Deep Reinforcement Learning algorithms (PPO, SAC, MA-POCA, self-play).
 2. Support for learning from demonstrations through two Imitation Learning algorithms (BC and GAIL).
 3. Quickly and easily add your own custom training algorithm and/or components.
  4. Easily definable Curriculum Learning scenarios for complex tasks
  5. Train robust agents using environment randomization
 6.  Utilizes the Sentis to provide native cross-platform support
  7. Unity environment control from Python



# What you will see when you run the simulation...

1. First, notice how the bird move at different rate. 

2. The bird is moving to the front and also moving back to its point.  

3. Wait for the point where the bird is satisfied with the job it has done in the first two tiles.
It will then move around and stop again.

4. So, the bot will go into turbo mode - which will spam warning messages in the console telling you that is turbo mode.  To make this easier to see you may,
  want to toggle the normal debug messages in the unity editor.

6. Then it will move on to the next tile. you will Notice that the bot goes into turbo mode only on the tile but quickly switches off to normal mode when it moves off it. 
That's because turbo mode has a lower efficiency rate.

7. and lastly it prefers to be in normal mode whenever it can. 


Quick Start;

a. Create a new project in unity,
b. Clone this repository in the root project folder,
c. Delete sample scene from your Unity project if it exists and switch to the MovingAgent scene in the scene folder and Press Play...

This project is done in Unity 6000.0.15 with the UnityProlog framework

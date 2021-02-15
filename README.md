# Udacity-CVND-P3-SLAM
Graph SLAM implementation for Landmark Detection in a 2D world. The set of ipynb files, first setup a 2D world with a robot and landmars and then implements SLAM.

## Files in this repository
1. Notebook 1 : Robot moving and sensing
    - This notebook creates a robot in a 2D world, and some landmarks around the robot. Also implements a **Sense** function that detects distance between the robot and the landmarks around the robot.
  
2. Notebook 2 : Omega and Xi, Constraints
    - Representing the robots motion and landmarks detected using Omega and Xi
    
3. Notebook 3 : Landmark detection and tracking
    - The implementaiton in a 2D world. 
    **The basic requiremment of the project was to implement SLAM (offline mode). I have also implemented online SLAM in which omega only keeps track of the latest robot pose (you do not need all of them to implement slam correctly).
    
4. robot_class.py : Robot object with its world
    
5. helpers.py : helper functions
    - Display functions

## Execution
Clone this repo and execure the Notebook 3 . The number of landmarks, timesteps and world size are configurable parameters in the notebook. 

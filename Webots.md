# Webots Simulator Labsheets

The following Labsheets will guide you to write code to operate a simulated e-puck robot. The Labsheets are designed to guide you through an incremental process of establishing the skills you need to operate the e-puck robot to solve and evaluate difficult tasks. 

<p align="center">
  <img src="https://github.com/paulodowd/EMATM0053_21_22/blob/main/images/Webots_ArenaFloor.png?raw=true">
 </p>

Labsheet 0 will guide you through installing the necessary simulator software, <a href="https://cyberbotics.com/">Webots</a>.  Once installed and setup, you should be able to see a representation of the Line Following Challenge, as above.  The line has been designed to present specific challenges to your robotic system development. This Line Following Challenge can be broken down into the following elements:

- Driving in a straight line, from either starting box.
- Joining the Line at a 90° angle.
- Traversing corners of various types: e.g. 45°, 90°, in either direction.
- Traversing curves, in either direction.
- Traversing a gap in the line.
- Driving around the pink box obstruction without collision.
- Identifying the end of the line.
- Returning home (to where the robot started).
- Writing a general solution to solve the line traversal in either direction.

In approaching this task, you are encouraged to first of all simplify the problem(s) where necessary. Later, you are encouraged to explore more difficult configurations of the line. The objective of this task is to test and develop your skill. You will later draw on your skill to produce an insightful and meaningful experiment utilising the Webots simulation of an e-puck as part of your Summative Assessment for the unit.

The following additional materials available to you:
- A zip file containing the Webots simulator world and a template e-puck controller (<a href="https://github.com/paulodowd/EMATM0053_21_22/tree/main/WebotsWorld">Github Page</a>, <a href="https://github.com/paulodowd/EMATM0053_21_22/raw/main/WebotsWorld/Webots_Labs.zip">Download Link</a>).
- The original .svg file used for the simulated arena floor, which you can modify to produce your own task environments (<a href="https://github.com/paulodowd/EMATM0053_21_22/tree/main/WebotsFloor">Github Page</a>, <a href="https://github.com/paulodowd/EMATM0053_21_22/blob/main/WebotsFloor/test_floor.svg">Download Link</a>).  <a href="https://inkscape.org/">Inkscape</a> is a free and accessible svg graphics editor.

# Labsheets

These labsheets will not provide you will the final solution for the Line Following Challenge. Instead, they provide all the necessary "ingredients", and you have the creative task of developing a fully integrated solution.

### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/L0_Webots_GettingStarted.ipynb)  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/L0_Webots_GettingStarted.ipynb) Labsheet 0: Getting Started in Webots 

### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/L1_Moving.ipynb)  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/L1_Moving.ipynb) Labsheet 1: Moving 

###  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/L2_LineFollowing.ipynb)  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/L2_LineFollowing.ipynb) Labsheet 2: Line Following

### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/L3_FiniteStateMachine.ipynb)  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/L3_FiniteStateMachine.ipynb) Labsheet 3: Finite State Machine

### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0053_21_22//blob/main/WLabsheets/L4_ObstacleAvoidance.ipynb)  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/L4_ObstacleAvoidance.ipynb) Labsheet 4: Obstacle Avoidance

### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/L5_Odometry.ipynb)  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/L5_Odometry.ipynb)  Labsheet 5: Odometry

### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/L0_Webots_GettingStarted.ipynb)  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/L0_Webots_GettingStarted.ipynb) Labsheet 6: PID 

### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/L7_Mapping.ipynb)  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/L7_Mapping.ipynb)  Labsheet 7: Mapping 


## Supplementary Labsheets

### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/SL0_WebotsDataCollection.ipynb)  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/paulodowd/EMATM0053_21_22/blob/main/WLabsheets/SL0_WebotsDataCollection.ipynb)  S. Labsheet 0: Collecting Data, Adjusting the Simulator 



## Suggested Reading
<a href="https://www.sciencedirect.com/science/article/pii/S0921889014000967?via%3Dihub">Webots Reality Gap</a>


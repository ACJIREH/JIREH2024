Engineering materials ====

The implementation of a solution for an autonomous vehicle is related to the development of technologies that make the transportation of both passengers and merchandise more efficient and safer. This type of vehicle receives signals from the average environment from SR HC-04 ultrasound sensors that are processed by an Arduino Uno card which, using the IDE programming platform, configures the action to be performed depending on the signal received by each sensor. . This vehicle has 4 ultrasound sensors located at the front, sides and front. To carry out this task, the program has several functions such as: advance that allows the vehicle to move as long as there are no obstacles in front, once the distance between the vehicle and the wall is less than 90 cm, it starts a cross to the side with the greatest distance, which is achieved through the lateral sensors, left or right. If the reading on the left is greater than that on the right, the crossing is done to the left, otherwise it is done to the right.   
Likewise, it has a function that allows you to calculate the angle, using trigonometric functions, which will allow you to stay away from the side walls, thus avoiding colliding with the sides. 
In order to determine the number. of laps, variables were defined that allow keeping a record of the laps to know when to stop, having completed the three laps.


## Contenido

* `t-photos` contains 2 photos of the team (an official one and one funny photo with all team members)
* `v-photos` contains 6 photos of the vehicle (from every side, from top and bottom)
* `video` contains the video.md file with the link to a video where driving demonstration exists
* `schemes` contains one or several schematic diagrams in form of JPEG, PNG or PDF of the electromechanical components illustrating all the elements (electronic components and motors) used in the vehicle and how they connect to each other.
* `src` contains code of control software for all components which were programmed to participate in the competition
* `models` is for the files for models used by 3D printers, laser cutting machines and CNC machines to produce the vehicle elements. If there is nothing to add to this location, the directory can be removed.
* `other` is for other files which can be used to understand how to prepare the vehicle for the competition. It may include documentation how to connect to a SBC/SBM and upload files there, datasets, hardware specifications, communication protocols descriptions etc. If there is nothing to add to this location, the directory can be removed.

## Introduction



## How to prepare the repo based on the template

_Remove this section before the first commit to the repository_

1. Clone this repo by using the `git clone` functionality.
2. Remove `.git` directory
3. [Initialize a new public repository on GitHub](https://github.com/new) by following instructions from "create a new repository on the command line" section (appeared after pressing "Create repository" button).

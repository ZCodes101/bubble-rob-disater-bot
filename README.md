# Bubble Rob Disater Bot. AI in Robotics

## Deigned a realistic recovery environment for a robot to navigate through obstacles, find survivors, and alert first responders if found.  

- The disaster recovery environment is a representation of a building that collapsed on itself. The obstacles used were fire, beams from the ceiling, piles of concrete rubble, and chunks of drywall. The placement of the flag acts as a survivor stuck or trapped amid it all. There is also smoke scattered, which acts as dust filling the air of the depreciating structure. 

- The robot will improve disaster recovery in this environment with the listed obstacles by introducing realistic elements that it will encounter. The fallen chunks of drywall, concrete rubble, and wooden ceiling beams act as avoidable objects, which the bot must decide to go around or climb over if possible. Placing pockets of flames and the survivor adds a goal-oriented task to the scenario.

- The robot is small enough to navigate through the collapsed area, it maps the area and sends data back to first responders with information such as potential danger or survivors found. The sensors I’ve added were a survivor sensor, a fire path sensor and navigational sensors. The survivor nose sensor scans the area and send an S.O.S to alert rescue teams that a survivor was found. The fire sensor alerts the first responders that there is a path on fire. I’ve also added 2 navigational sensors, one on each side of the bot to help make better turns while navigating if the sensor comes near an object such as the drywall and concrete rubble. 

- The robot uses its various sensors to aid with the implementation of reasoning, knowledge representation, uncertainty, and intelligence. The robot makes decisions based on its reasoning about the objects it may encounter. If a path is blocked while in flames, the bot alerts the rescue team then moves out of danger instead of stopping and melting. Then proceeds to look for the survivor. When the bot locates the survivor with the sensor, it sends a distress signal with the survivor's location instead of ignoring them. Here you can also see its intelligence, completing the goal of finding a survivor and sending for help. During the process, the environment itself is unknown. This aspect of uncertainty is the object the bot may encounter, such as the walls, piles of rubble, and fallen debris. The robot gains knowledge from this environment using its navigational sensors. If an object is in the proximity of the bot, it will make the required maneuvers to navigate to avoid it if possible.


## Table of Contents

- [Installation](#installation)
- [Video](#video)
- [Tools](#tools)

## Installation
To run the app:  
- Download CoppeliaSim V4.3.0 rev3 for Windows https://www.coppeliarobotics.com/downloads
- Open the bubbleRob.ttt file from your destinated download folder

## Video
- To run video download rob.mp4 file and watch it in your prefered video player.

## Tools
- LUA
- Machine Learning


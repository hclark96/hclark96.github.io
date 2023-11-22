---
title: "Multirobot Adaptive Navigation"
last_modified_at: 2023-11-21T16:20:02-05:00
categories:
  - Blog
tags:
  - Post Formats
  - readability
  - standard
---
![The SCU Pioneer 3 fleet](/assets/images/pioneers.jpeg)

When multiple individual robots are made to function together as a group, new possibilities for control, navigation, and function are opened. Among these is what is called “adaptive navigation,” where the nature and topography of unmapped scalar and vector fields is mapped out while traveling within them, as opposed to thoroughly scanning the field to map it out beforehand. The SCU Robotic Systems Lab has previously had multiple projects explore the technology and methodology for utilizing this method with multiple robots, and it continues to be a topic with great potential for further study.
The focus of this particular branch of the project was to enhance the lab’s fleet of Pioneer 3 mobile robots with modern hardware and control, and then develop and implement software to allow for intercommunication, which is necessary for the computations needed for adaptive navigation. All rovers were updated with Nvidia Jetson processors, along with state of the art Roboteq controllers. Also integrated was a sensor suite including GPS, an IMU, Lidar, and more. Using these components, the robots were first programmed to execute point-to-point commands in a follow-the-leader formation, and are now being tested utilizing adaptive navigation methods.

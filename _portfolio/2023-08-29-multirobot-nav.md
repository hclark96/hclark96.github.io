---
title: "Multirobot Control"
excerpt: "Modernizing a fleet of rovers to explore adaptive navigation."
header:
  teaser: /assets/images/pioneer-small.jpeg
sidebar:
  - title: "Role"
    text: "Project Lead"
  - title: "Responsibilities"
    text: "Software development, robot assembly, part manufacturing, testing, etc."
---
![The SCU Pioneer Fleet](/assets/images/pioneers.jpeg)
When multiple individual robots are made to function together as a group, new possibilities for control, navigation, and function are opened. Among these is what is called “adaptive navigation,” where the nature and topography of unmapped scalar and vector fields is mapped out while traveling within them, as opposed to thoroughly scanning the field to map it out beforehand. The SCU Robotic Systems Lab has previously had multiple projects explore the technology and methodology for utilizing this method with multiple robots, and it continues to be a topic with great potential for further study.

The focus of this particular branch of the project was to enhance the lab’s fleet of Pioneer 3 mobile robots with modern hardware and control, and then develop and implement software to allow for intercommunication, which is necessary for the computations needed for adaptive navigation. All rovers were updated with Nvidia Jetson processors, along with state of the art Roboteq controllers. Also integrated was a sensor suite including GPS, an IMU, Lidar, and more. Using these components, the robots were first programmed to execute point-to-point commands in a follow-the-leader formation, and are now being tested utilizing adaptive navigation methods.

These robots are programmed using C++/Python and ROS2. All code can be viewed [here.](https://github.com/hclark96/pioneer-ii)

---
title: "Penny Arcade Cabinet"
excerpt: "A quick class project designing an arcade game."
header:
  teaser: /assets/images/pennyarcadesmall.jpeg
sidebar:
  - title: "Role"
    text: "Project Lead"
  - title: "Responsibilities"
    text: "Design, software development, manufacturing and assembly."
---
![Are You Smarter than a Box?](/assets/images/pennyarcade.jpg)

This was a quick but fun final project for a Mechatronics course. The cabinet was a variation on the classic "Simon Says" game, where a sequence is generated and gradually shown to the player, with each correct response adds an additional entry to the end of the sequence. For added flavor, a coin slot is used to start the game, and an internal servo rotates the central stage (each entry in the sequence has an associated rotation that is performed, before returning to the starting position at the end of the sequence). The score is conveyed to the player using 3D printed split-flaps, which are actuated using a pair of stepper motors.
The game is powered using a 9V AC adapter and is controlled by an internal Arduino MEGA64 board.

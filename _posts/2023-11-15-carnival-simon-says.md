title: "Penny Arcade Cabinet"
date: 2023-11-15T15:34:30-04:00

categories:
- Blog
tags:
- Post Formats
- readability
- standard
---
![Are You Smarter than a Box?](/assets/images/pennyarcade.jpg)

This build was a quick but fun final project for a Mechatronics course. The cabinet was a variation on the classic "Simon Says" game, where a sequence is generated and gradually shown to the player, with each correct response adds an additional entry to the end of the sequence. For added flavor, a coin slot is used to start the game, and an internal servo rotates the central stage (each entry in the sequence has an associated rotation that is performed, before returning to the starting position at the end of the sequence). The score is conveyed to the player using 3D printed split-flaps, which are actuated using a pair of stepper motors.
The game is powered using a 9V AC adapter and is controlled by an internal Arduino MEGA64 board.
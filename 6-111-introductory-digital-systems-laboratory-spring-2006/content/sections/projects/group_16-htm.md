---
course_id: 6-111-introductory-digital-systems-laboratory-spring-2006
layout: course_section
parent_title: Projects
title: Group 13
type: course
uid: 3ea448054a81c28122f11f62c8c8d827

---

Groups: [1]({{< baseurl >}}/sections/projects/group1) | [2]({{< baseurl >}}/sections/projects/group_2) | [3]({{< baseurl >}}/sections/projects/group_3) | [4]({{< baseurl >}}/sections/projects/group_5) | [5]({{< baseurl >}}/sections/projects/group_6) | [6]({{< baseurl >}}/sections/projects/group_7) | [7]({{< baseurl >}}/sections/projects/group_8) | [8]({{< baseurl >}}/sections/projects/group_9) | [9]({{< baseurl >}}/sections/projects/group_10) | [10]({{< baseurl >}}/sections/projects/group_11) | [11]({{< baseurl >}}/sections/projects/group_13-htm) | [12]({{< baseurl >}}/sections/projects/group_14-htm) | 13 | [14]({{< baseurl >}}/sections/projects/group_18-htm) | [15]({{< baseurl >}}/sections/projects/group_19-htm)

Audio-Driven Laser Tetris
-------------------------

By Cameron Lewis and James Sun

Abstract
--------

The purpose of this project is to demonstrate an advanced version of the classic arcade game Tetris. Our version boasts a much more dynamic and random game-play experience than conventional implementations, bringing new meaning to the concept of background music. Users will manipulate the falling objects as in the traditional game, but there will be several twists. The entire game will be driven by music and then projected onto a large screen using a laser raster system. In addition, more detailed game graphics along with other audio-based effects will be displayed on a VGA monitor connected to the FPGA Labkit.

The audio-based elements of the game will operate in the following manner: the drop rate of the game pieces will be controlled by music frequencies and magnitudes. The audio input to the system will be connected to the AC97 audio decoder on the Labkit which will digitize the analog signals and pass them into the FPGA for processing.

The video components will be comprised of two display elements. First will be the high resolution VGA imaging module, which will display the complete Tetris game with scores, settings, and other game errata. Second will be the laser display, which will interface with the core graphics output of the Tetris game by a separate laser controller module - whose job will be to rapidly modulate the output of the laser at appropriate times as to create a low resolution, scanning raster image of the Tetris playing field.

Project Files
-------------

Presentation ([PDF]({{< baseurl >}}/sections/projects/presentation13))

Report ([PDF]({{< baseurl >}}/sections/projects/project13))

Report Appendix ([PDF]({{< baseurl >}}/sections/projects/appendix13))
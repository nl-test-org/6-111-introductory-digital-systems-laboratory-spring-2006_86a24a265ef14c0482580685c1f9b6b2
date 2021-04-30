---
course_id: 6-111-introductory-digital-systems-laboratory-spring-2006
layout: course_section
parent_title: Projects
title: Group 9
type: course
uid: adfdd650b23d826e2a98f527493aba1b

---

Groups: [1]({{< baseurl >}}/sections/projects/group1) | [2]({{< baseurl >}}/sections/projects/group_2) | [3]({{< baseurl >}}/sections/projects/group_3) | [4]({{< baseurl >}}/sections/projects/group_5) | [5]({{< baseurl >}}/sections/projects/group_6) | [6]({{< baseurl >}}/sections/projects/group_7) | [7]({{< baseurl >}}/sections/projects/group_8) | [8]({{< baseurl >}}/sections/projects/group_9) | 9 | [10]({{< baseurl >}}/sections/projects/group_11) | [11]({{< baseurl >}}/sections/projects/group_13-htm) | [12]({{< baseurl >}}/sections/projects/group_14-htm) | [13]({{< baseurl >}}/sections/projects/group_16-htm) | [14]({{< baseurl >}}/sections/projects/group_18-htm) | [15]({{< baseurl >}}/sections/projects/group_19-htm)

A Two-Input Polygraph
---------------------

By Chris Buenrostro, Isaac Rosmarin, Archana Venkataraman

Abstract
--------

In this project we propose to design and implement a 2-input polygraph using the Xilinx Virtex2 FPGA. The two physiological signals that we will focus on are pulse rate and skin conductivity. These inputs were chosen because they are fairly easy to measure and interpret. During times of emotional stress, such as when the subject is forced to lie, his pulse rate increases. Likewise, the subject is more likely to sweat, thus increasing his skin conductivity.

The project will be divided into three portions: the Physiological Sensor Block, the Digital Control Block, and the Display Block. The sensor block will focus on extracting data from the analog sensors used to measure pulse and skin conductivity. It will involve assembling the two sensors needed for the project, interfacing with an analog-to-digital converter (ADC), and storing the results in a Block RAM. The digital control block is the major control unit for the project. Although it will provide for both user interaction and memory access, most of this section will focus on analyzing data from the sensor. Since the subject is asked several control questions which serve as a baseline, the system must be able to identify different types of questions and algorithmically analyze the physiological signals appropriately. The display block will focus on outputting the measurements and the results. Just as conventional polygraphs record the physiological data using pen and paper, we would like to display the sensor outputs and the computer's decision on the monitor. This portion will provide for additional features such as screen capture, so data can be compared visually.

Project Files
-------------

Presentation ([PDF]({{< baseurl >}}/sections/projects/presentation9))

Report ([PDF]({{< baseurl >}}/sections/projects/project9))

Report Appendix ([PDF]({{< baseurl >}}/sections/projects/appendix9))
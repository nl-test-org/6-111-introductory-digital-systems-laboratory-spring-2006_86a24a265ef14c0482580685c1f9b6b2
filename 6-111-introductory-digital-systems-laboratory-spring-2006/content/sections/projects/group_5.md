---
course_id: 6-111-introductory-digital-systems-laboratory-spring-2006
layout: course_section
parent_title: Projects
title: Group 4
type: course
uid: b2eb79ee186114d38a6026d864e56d26

---

Groups: [1]({{< baseurl >}}/sections/projects/group1) | [2]({{< baseurl >}}/sections/projects/group_2) | [3]({{< baseurl >}}/sections/projects/group_3) | 4 | [5]({{< baseurl >}}/sections/projects/group_6) | [6]({{< baseurl >}}/sections/projects/group_7) | [7]({{< baseurl >}}/sections/projects/group_8) | [8]({{< baseurl >}}/sections/projects/group_9) | [9]({{< baseurl >}}/sections/projects/group_10) | [10]({{< baseurl >}}/sections/projects/group_11) | [11]({{< baseurl >}}/sections/projects/group_13-htm) | [12]({{< baseurl >}}/sections/projects/group_14-htm) | [13]({{< baseurl >}}/sections/projects/group_16-htm) | [14]({{< baseurl >}}/sections/projects/group_18-htm) | [15]({{< baseurl >}}/sections/projects/group_19-htm)

Fingerprint Verification System
-------------------------------

By Bashira Chowdhury and Cheryl Texin

Abstract
--------

We will design and implement an image recognition system to identify fingerprints based on a given database. We will begin by inputting simple images and checking that the system accurately identifies those images. As the system is developed, more complex images can be used. The final stage of the project will involve identifying an individual's fingerprint based on standard points of identification used in common practice.

This project consists of a few stages. The initial stage will involve creating a database in memory for the image comparison. The next stage will be developing an interface between the camera and a RAM to store the image that needs to be identified. Once the image has been loaded into the system, it must be processed to select the appropriate characteristics for the comparison to the database. The processed image will then be compared to the images in the database to determine the quality of the similarities. The most similar image will be selected and presented to the user interface along with the quality of the identification.

The image processing will involve a series of filters in the spatial domain. There will be an edge-detection filter to sharpen the image, prior to binarization of the fingerprint. Another filter will select the unique components of the fingerprint. The database will contain the post-processed fingerprint information to minimize the size of the stored data. The database size will be limited to the memory of the labkit, which will be sufficient to demonstrate the functionality of the fingerprint matching system.

The work will be split into two components. Bashira will be responsible for interfacing the camera to the labkit, as well as managing the data storage in memory. Cheryl will implement the image processing to isolate the data for the analysis and the matching. Once the fingerprint recognition scheme is working, both team members will work to enhance the identification interface as time allows to create a visually appealing result.

Project Files
-------------

Presentation ([PDF]({{< baseurl >}}/sections/projects/presentation4))

Report ([PDF]({{< baseurl >}}/sections/projects/project4))

Report Appendix ([PDF]({{< baseurl >}}/sections/projects/appendix4))
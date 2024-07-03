## Project Digital Twin Nibelungenplatz (v4) 

- This project aims to create a digital twin of the Nibelungenplatz crossroad area in front of the Frankfurt UAS.
- This is version 4.0 of the project. Versions 3, 2 and 1 of the project was done previously .
- Project Owner (PO): Prof. Dr. Karsten Weronek, coordinated with Dassault Systèmes.
- Master project for High Integrity  Systems at The Frankfurt University of Applied Sciences

## **Project background / Introduction**

The purpose of this project is to construct a 3D Digital Twin (simulation) of the square of Nibelungenplatz taking in consideration of the traffic management, emergency response planning, etc. This is an ongoing project and we have to produce the fourth version (.v4) and the scope and milestones will be decided considering the last semesters’ outcome and improvements.

## **Business case / Benefits of doing this project**

Some of the advantages of implementing this project are:

- A detailed visual representation of the Nibelungenplatz square.
- Evaluation of the impact of potential changes
- Understanding the site’s design and functionality
- Identifying potential safety hazards

## **Objectives and scope**

Major Objectives:

- Collecting and preparing data form different resources (city-provided, maps, urban plans, videos recordings etc)
- To create a highly detailed and accurate 3D Digital Twin of Nibelungenplatz including buildings, trees, streets, cars, bicycles, pedestrians etc.
- Visualizing on Dassault 3D platform.
- Improving the video quality without compromising GDPR.

## **Deliverables / Outcomes**

A new version of 3D Digital Twin of Nibelungenplatz square was created

## **Milestones**

The following milestones was achieved 

### Milestone 1: Video Recording

- Determine camera positions, camera height, camera angle
- Fix the configuration: frame rate, video length, resolution
- Decide the no of video sets and video duration
- Height should be as high as possible, video should be stable
- camera angle should be perfect.

### Milestone 2: Configure Static Data in Dassault 3D Platform

- Figure out why the city data was not usable and possibly, fix it
- Dassault dashboard using static data (tree, building, camera coordinates)

### Milestone 3: Merge Data of All Cameras

- Understand the code from summer22
- One single data file containing information , i.e. Merge five JSON files after calculating the real world co-ordinates
- Prepare a prototype or model to show the ideas on merging the coordinates
- be able to use the file on Dassault platform

### Milestone 4: Detect Objects (Bike and Pedestrians using YOLO)

- Train YOLO model
- Detect bikes and pedestrians in the videos
- be able to maintain the consistency of the detected object

### Milestone 5: Improve Object Detection Performance

- Extract reference points from video file
- Calculate orientation of moving vehicles
- Improve the orientation calculation
- be able to keep the movement of the vehicles on the Dassault platform smoother

### Milestone 6: Visualize on Dassault Platform

- Configure static data
- Create widget using dynamic data
- Create the digital twin on Dassault platform

## **Team Composition**

### Team Setup

Member of 12 worked together as a team on different part of the project to provide updated version of the project.

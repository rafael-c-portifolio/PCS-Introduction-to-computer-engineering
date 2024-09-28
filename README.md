
# Smart Pill Organizer with App Support - PCS3100 Introduction to Computing Engineering
This project was completed as part of the PCS3100 - Introduction to Computing Engineering course. The project was a free-theme group assignment, and our group chose to develop a Smart Pill Organizer with an accompanying app as a Minimum Viable Product (MVP). The project aimed to combine hardware (an Arduino-based organizer) with software (app functionality) to help users manage their medication intake.

# Project Overview
The primary goal was to design and prototype a Smart Pill Organizer that helps users track and manage their medications. The organizer, powered by Arduino, included buttons to simulate interaction with a cloud-based system where the app would store and manage data.

# Features of the MVP:
The hardware component (Arduino) served as the pill organizer controller.
When a button was pressed, it simulated the organizer sending data to the cloud.
The app (simulated in C code) managed basic functions like labeling medications, time-stamping when pills were taken, and keeping a log of what was taken and when.
# Design Process
Hardware (Arduino):

The Arduino was equipped with buttons to represent different pill compartments. Each button, when pressed, triggered an LED flash to simulate data being sent to the cloud.
The hardware component was kept simple to represent a proof of concept, focusing on the smart organizer's basic functionality.
Software (MVP Code in C):

The C code developed for the MVP simulated core functions of the app. These included:
Labeling Medication: Users could input the names of medications.
Time Stamping: The system would time-stamp when a medication was taken.
Medication Logs: The app kept a record of what medications were taken and at what time.
While the actual app wasn't fully developed, the code provided the foundation for how the app would interact with the pill organizer via cloud services.

# Challenges and Learning Outcomes
Hardware and Software Integration: One of the primary challenges was simulating the interaction between the hardware (Arduino) and the cloud-based app system. This required understanding both hardware and software aspects of computing engineering.

Developing a Functional MVP: Creating an MVP with basic but essential features was a valuable exercise in project scoping, focusing on key functionalities (labeling, time-stamping, and logging) before building a fully-featured product.

Working with Arduino and C: The project required students to learn and apply Arduino programming and C language, both critical in simulating the core functionalities of the Smart Pill Organizer.

# Materials and Tools
Arduino: Used to simulate the pill organizer and its interaction with the app.
Buttons and LEDs: Represented the pill compartments and their actions.
C Programming Language: Used to develop the MVP’s app functionality simulation.
Conclusion
The Smart Pill Organizer project provided an opportunity to explore both hardware and software aspects of computing engineering. By developing a basic MVP using Arduino and C, we gained valuable hands-on experience in integrating physical components with software systems, simulating how a real-world IoT device could interact with cloud services and an app for user management.
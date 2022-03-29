# sensorhub-project
#  Project Explanation
This project is designed to be a working proof of concept in the feasibility of running an edge computing solution that collects environmental data around the clock with little to no downtime. This project is not designed as a specific solution to an existing problem, but rather an exploration of feasible avenues for edge computing.
A local website will be hosted on my project that is accessible through wireless networking via an ip-address. This website will be showcasing live local data. These data will be temperature, humidity, barometric pressure, and light-level.

# Components
[[insert table]]

# Project Timeline
## 02/11/2022
All of the hardware required for this project has arrived and I have assembled it together.
## 02/17/2022
I have successfully installed NGNIX, php, phpmyadmin, and MariaDB onto pi1 and they are accessible from other devices.
## 02/21/2022
I have moved the database to pi1's external flash drive and shared its directory to pi2 and pi3 exclusively.
## 02/22/2022
I have successfully implemented the software required for viewing the camera stream from pi2. The camera feed is accessible via web-interface.
## 03/15/2022
I have modified the code needed to read information from the SenseHat to work with the DockerPi SensorHub.
I am currently trying to get urllib working with python so that I can add the information to my database.
## 03/17/2022
I have hit a roadblock in that the python and php code that I have written isn't working correctly. I keep getting error 500 on my ngnix webserver. Troubleshooting is necessary.
## 03/22/2022
I have successfully gotten urllib working within python and have successfully fixed my code so that everything else is working!
The webpage is successfully served and can be accessed from a remote device on the same network.
## 03/26/2022
I have decided to remove the camera element from this project, since between the time I started, and now, updates to the Raspberry Pi Kernel have made this implementation impossible to achieve. The environment sensing element is still the main focus of this project. Additionally, I have begun work on the project blog today.

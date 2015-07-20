---
layout: default
---
![alt text](http://i.imgur.com/OgFH1fO.png)
#Vehicle Infotainment Center

####Goal
Develop an open source UI infotainment platform for vehicles that communicates with vehicle hardware and cloud based services to deliver media, autopilot, driving statistics and diagnostics in order to enhance safety and user experience.

##Features
* Full vehicle control over CAN
  * Media
  * Climate control
  * Seat position
* Navigation
  * Using Google maps API
  * Optimized for hybrid
* Autopilot features
  * Lane assist
  * Backup assist
  * Parking assist
  * Optimization features
* Statistics
  * Hybrid drivetrain
  * Fuel efficiency
  * Battery information
  * Low fuel/charge Warning
  * Driver statistics
* Media control
  * Local/Bluetooth Music Player
  * Web browser
  * Email/Calendar/Notifications
  * Cloud radio
  * Auto playlists
* Mobile Phone Integration
  * IOS and Android
  * Bluetooth handsfree
  * Remote controlled features
    * Climate control
    * Smart Charging
    * Find my car
* Safety
  * Eye Tracking
  * Autopilot assist
  * Warning tones

####Design
The canvas will be a touchscreen interface with simplicity as the forefront of the UI. Unlike a phone which is always in near the users face, this will be a supplement the the driving experience and not a distraction. This means the design focus will be smoothness and ease of use rather than animations and flashy menus. All main functions must be easily accessible and executable with minimal driver distraction. Interfaces will include the main screen, and a mobile app with the possibility of a HUD or cluster display.

####Engineering
We have a pre-existing [Github repository](https://github.com/UWEcoCAR/UWCenterStack) with an old build to start from. This was written in Javascript and utilizes the Node webkit and Ruby Sass. It is run on a Debian linux kernel on a mini computer. Developers will use a distributed VM or embedded device for development We are open to building off of this or starting from scratch depending on the team's input. We also have CAN drivers for interfacing with the lower level vehicle controls. We have plans for using python scripting for some of the backend media daemons and Google's maps api for navigation. Autonomous related features will likely utilize OpenCV and machine learning libraries in python. Many of these elements are flexible and up for discussion.

##Team
This project is a subset of the [UW EcoCAR 3](http://uwecocar.com/index.html) project which is a funded four year project that involves converting a 2016 Camaro into a cutting edge hybrid. We will be using the Camaro as a test vehicle for the infotainment system, however the design intent is to make it compatible with all modern vehicles. The vehicle lab is located on the UW campus and will be accessible by those on the team.

This is a university funded project, with learning as a priority. This doesn't necessarily mean you need to be a University student, but there will not be any pay compensation, at least for now. There are opportunities for school credit and internships/jobs. We do have a headcount limit, so if there is enough interest the application process may become competitive.

The team will be multidisciplinary and not very restrictive as to who can join. That being said, there are a few requirements listed below.

#####Team requirements
  * Self learner
  * Time to contribute
  * Idea of what you want to contribute

The listed UW departments listed will be contacted as well. If you are a student or prospective student any any of these majors, this project is probably for you!

#####Majors
* Computer Science/Engineering
* Design school
* Electrical Engineering
* Human Centered Design & Engineering
* Information school
* Industrial Engineering
* Business school

Here is a rough idea of the roles we will be filling. These roles will likely become small subteams

#####Roles
* Frontend design (UI/UX)
* Backend architecture
* Embedded programming
* Signal and image processing
* Project management

The outlined skills provide an idea of the projected disciplines and programming environments we plan on utilizing.  The skills listed are preferred but not a requirement to join but provide some insight into what we will be dealing with.

#####Skills
This is a software, hardware and design project driven by data and user experience.

* UI/UX design
* Linux and virtual machine familiarity
* Computer Vision and machine learning
* Knowledge of CAN protocol (UDS, ODX)
* Data science
* Github version control
* Programming
  * NodeJS
  * Ruby (Sass)
  * CSS/HTML
  * Embedded C
  * IOS and Android
  * Python and Bash scripting
  * Google maps API
  * Cloud networking
  * Music Player Daemon (MPD)
  * Matlab

#####Expectations
We expect a minimum of 8 hrs per week from everyone on the team, however depending on your role and level of commitment this will obviously grow. UW EcoCAR team members considered as 'dedicated' easily spend 30+ hrs a week on the project. Those considered dedicated will likely have leadership and travel opportunities.

##Apply
For now contact Jake Garrison directly at <jakehgarrison@gmail.com> with some background info and what you are hoping to contribute and why you are interested. You may also apply more formally [here](https://catalyst.uw.edu/webq/survey/jlgoin/243177), but this application is not specific for this project.

Fork this project on [Github](https://github.com/jake-g/Vehicle-Infotainment-Center)

###### 2016 Camaro
We get one of the first ones off the factory line and are making it a super fast hybrid! You can be part of this.

![alt text](http://media.caranddriver.com/images/15q2/657945/2016-chevrolet-camaro-official-photos-and-info-news-car-and-driver-photo-658629-s-429x262.jpg "2016 next gen Camaro")

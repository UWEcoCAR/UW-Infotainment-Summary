---
layout: default
---
![alt text](https://github.com/jake-g/Vehicle-Infotainment-Center/raw/gh-pages/_images/banner.png)

#Vehicle Infotainment Center

####Goal
Develop an open source UI infotainment platform for vehicles that communicates with vehicle hardware and cloud based services to deliver media, autopilot, driving statistics and diagnostics in order to enhance safety and user experience.

####Impact
The automotive industry is flooded with dated, proprietary technologies. With the growing number of open source projects and communities on the internet, now is a great time to help push the open source wave into the automotive market. Ford has recently opened some of it's technology by providing a very limited API, and Tesla is shattering standards by releasing patents. There has yet to be a truly open source, extendable infotainment system for vehicles. We want to change that.

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
The canvas will be a touchscreen interface with simplicity as the forefront of the UI. Unlike a phone which is always in near the users face, this will be a supplement the the driving experience and not a distraction. This means the design focus will be smoothness and ease of use rather than animations and flashy menus. All main functions must be easily accessible and executable with minimal driver distraction. If you have ever interacted with the UI of a modern car, you probably have noticed how dated, ugly and limited they are. We aim to bring the IOS and Android style interfaces that users are used to into the vehicle. Such interfaces will include the main screen, and a mobile app with the possibility of a HUD or cluster display.

####Engineering
We have a pre-existing [Github repository](https://github.com/UWEcoCAR/UWCenterStack) with an old build to start from. This was written in Javascript and utilizes the Node webkit and Ruby Sass. It is run on a Debian linux kernel on a mini computer. Developers will use a distributed VM or embedded device for development. We are open to building off of this or starting from scratch depending on the team's input. We also have CAN drivers for interfacing with the lower level vehicle controls. We have plans for using python scripting for some of the backend media daemons and Google's maps api for navigation. Autonomous related features will likely utilize OpenCV and machine learning libraries in python. Many of these elements are flexible and up for discussion.

##Team
This project is a subset of the [UW EcoCAR 3](http://uwecocar.com/index.html) project which is a funded four year project that involves converting a 2016 Camaro into a cutting edge hybrid. The vehicle lab is located on the UW campus and will be accessible by those on the team. We will be using the Camaro as a test vehicle for the infotainment system, however the design intent is to design it to be compatible with all modern vehicles. Some features, like the Camaro autopilot, will require NDA's and need to remain private. This is because they rely on donated cutting edge hardware that we could never afford. We can eventually generalize our algorithms to work on generic hardware that anyone can use.

This is a university funded project, with learning as a priority. This doesn't necessarily mean you need to be a University student, but there will not be any pay compensation, at least for now. There are opportunities for school credit and internships/jobs. We do have a headcount limit, so if there is enough interest the application process may become competitive.

####Team requirements
The team will be multidisciplinary and not very restrictive as to who can join. That being said, there are a few requirements listed below.

  * Self learner
  * Time to contribute
  * Idea of what you want to contribute

####Majors
The listed UW departments listed will be contacted as well. If you are a student or prospective student in any of these majors, this project is probably for you!

* Computer Science/Engineering
* Design school
* Electrical Engineering
* Human Centered Design & Engineering
* Information school
* Industrial Engineering
* Business school

####Roles
Here is a rough idea of the roles we will be filling. These roles will likely become small subteams

* Frontend design
* Backend architecture
* UI/UX
* Embedded programming
* Signal and image processing
* Project management

####Skills
The outlined skills provide an idea of the projected disciplines and programming environments we plan on utilizing.  The skills listed are preferred but not a requirement to join but provide some insight into what we will be dealing with.

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

####Expectations
We expect a minimum of 8 hrs per week from everyone on the team, however depending on your role and level of commitment this will obviously grow. UW EcoCAR team members considered as 'dedicated' easily spend 30+ hrs a week on the project. Those considered dedicated will likely have leadership and travel opportunities.

##Apply
Contact Jake Garrison directly at <jakehgarrison@gmail.com> with a resume (if you have one), some background info and what you are hoping to contribute and why you are interested. You may also apply more formally [here](https://catalyst.uw.edu/webq/survey/jlgoin/243177), but this application is not specific for this project.


###### 2016 Camaro
We get one of the first ones off the factory line and are making it a super fast hybrid! You can be part of this.

<br>
<div style="text-align:center"><img src ="https://github.com/jake-g/Vehicle-Infotainment-Center/raw/gh-pages/_images/cropped-camaro.png" /></div>

<br>
 <a href="https://github.com/jake-g/Vehicle-Infotainment-Center">View On <strong>GitHub</strong></a></li></div><div style="text-align:left">

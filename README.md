# BUILD YOUR OWN SELF-DRIVING CAR

This repository will present the topic of retrofitting a hobbyist car for the purpose of driving autonomously, as well as collecting a number of resources for making that goal a reality. We hope to see the rise of the Homebrew Computing Club for the autonomous vehicle industry, an opportunity for amateurs, students, and DIYers to participate in a way that is cheap, easy and fun.

MOOCs have given us unprecedented access to classroom learning, and from this democratization of knowledge, we’ve already seen a huge surge in creativity, collaboration and experimentation that comes from an open-source culture. We want to extend that all the way to the hardware and the sensors and prove that the software we write and the models we train can really hold their own under real world conditions.

### WHY?
  - **Democratize the technology**
    - The architecture of a self-driving RC car is not in principle different from that of a full-sized vehicle. This puts the full autonomous vehicle architecture within reach of anyone who wants to learn. You now have the ability to work with the full menu of sensors, micro controllers, motors, etc.
  - **Real world data beats canned video / simulation**
    - With the classes available, we have been able to write the algorithms for things like steering control, obstacle detection, and path planning. But having a physical platform allows us to move from working code to code that functions in real world conditions. (Udacity Simulator vs Real-time live footage)
  - **Safety and Cost**
    - Crashing an RC car is not a catastrophic event in the way that a full-size car crash is
    - Fear of catastrophic failure leads us to optimize for safety and for preserving precious equipment without really pushing the boundaries of what the technology can do.
    - On a cheap, small scale platform, we have the freedom to explore and experiment in ways that researchers working on full-sized cars cannot.
  - **Push the boundaries of Sensing, Perception and Control**
    - There’s a quote in Formula 1 racing, “If everything seems under control, you’re not going fast enough.” We want to push the limits of what our software and hardware can do. We want to move fast, break things, learn, and have fun!


### WHAT DOES IT TAKE TO BUILD?
  - **Chassis**
    - Magnet 1/16 ~$90
    - Traxxas 1/10 ~$300
  - **Sensors**
    - Camera: visual perception
    - Lidar: spatial/depth perception with pulsed laser range sensors
    - IR Depth Imaging: spatial/depth perception using projected infrared light and camera
    - IMU (Inertial Measurement Units): measures and velocity and angular rate using a combination of accelerometers and gyroscopes
    - Radar, Sonar, etc.
  - **Controller**
    - The sensors are interfaced with a computer or computers, onboard and remotely via Wifi, which gather than sensor data and relay it to the software
      - Raspberry Pi (Zero or 3) - Cheap, but less powerful, often delegates perception and planning to another computer, such as a laptop
      - Nvidia Jetson Series - More powerful micro-controller for onboard computation
      - Android, Beaglebone, etc.
  - **Software**
    - Open source software like ROS, OpenCV, Tensorflow, etc.
    - Perception and planning algorithms process and combine the sensor data and send back steering and throttle commands to the car

### HOW DO I GET STARTED?
Fortunately, there are already a number of guides we can follow to get started.

* **Simple: <$100**
  - Simple Raspberry Pi Car: https://diyrobocars.com/simple-raspberrypi-car/

* **Intermediate: $150-500**
  - RPi/Arduino: https://www.wilselby.com/research/autonomous-vehicles/diy-autonomous-vehicle-project/
  - Donkey Car: http://www.donkeycar.com/ 
  - Android Robocar: https://github.com/zugaldia/android-robocar
  - MonsterBorg: https://www.piborg.org/monsterborg-preorder

* **Advanced: $1000+**
  - Formula 1/10: http://f1tenth.org/car-assembly
  - BARC Project: http://www.barc-project.com/
  - MIT RACECAR: https://mit-racecar.github.io/ (also the helpful Jetson Hacks video series: https://www.youtube.com/playlist?list=PLXYLzZ3XzIbi3djynrdC1ofn-54WpIFbN)

## OTHER RESOURCES
  - **Education**
    - Udacity Self-driving Car Engineer Nanodegree: https://www.udacity.com/drive
    - Georgia Tech AI for Robotics: https://www.udacity.com/course/artificial-intelligence-for-robotics--cs373
    - Georgia Tech Control of Mobile Robotics: https://www.coursera.org/learn/mobile-robot
    - Formula 1/10 UPenn Lectures: http://f1tenth.org/lectures
    - MIT Deep Learning for SDC: http://selfdrivingcars.mit.edu/
  - **Community**
    - Donkey (Request invite to their Slack channel): http://www.donkeycar.com/
    - OSSDC (Also has a Slack channel): http://ossdc.org/
    - DIY Robocars (Meetups)
      - SF: https://www.meetup.com/DIYRobocars/
      - DC: https://www.meetup.com/DIYRobocarsDC/
      - Austin: https://www.meetup.com/DIYRobocarsATX/
      - NYC: https://www.meetup.com/DIY-Robocars-NYC/

## COMPETITIONS
Competitions are a great way to motivate the problem, focus our efforts, and get exposed to what people are doing in the world.
  - SparkFun AVC: https://avc.sparkfun.com/
  - Formula Pi: https://www.formulapi.com/
  - Formula 1/10: http://f1tenth.org/competition

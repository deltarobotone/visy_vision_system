# Welcome vision friends! 

This is a Rapsberry Pi 3 and Raspberry Camera V2 based vision system project for makers and students. An integrated neopixel light ring provides adjustable illumination for vision tasks. The status bar could be used to inform users quickly about different application states. The 3,5" touch screen on the backside of the system makes it possible to control applications for example or show the camera image directly on the system. The ROS (Robot Operating System) is the basic framework for software packages we defined for this system. The software functions are stored in ROs packages for illumination, camera, user interface, detectors, robot control and so on. The software is all open source and found at [deltarobotone](https://github.com/deltarobotone). You can use them and/or build your own packages. All in all the system provides a lot of features to develop, implement and use image processing tasks. If you want to use the system for your own propurses you can deactivate the autostart services of every visy package and develop some own cool apps.

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(61).PNG" width="400">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(61).PNG)

With the help of a community (this means you) it could be a world wide educational project. Working on this project is a lot of fun. Learning something about the different topics and share it with the world is realy great. Be part of it...

#### [***>>>How to build you visy<<<***](https://github.com/deltarobotone/visy_vision_system/wiki)

# Visy system image

Visy comes with a Raspberry Pi 3 system image including

- Ubuntu 16.04 LXDE Desktop 
- ROS Kinetic
- ROS workspace including all visy packages
- Autostart sevices for visy packages
- 3.5" touchscreen driver

Download the image using the link below and follow the instructions at [visy wiki page](https://github.com/deltarobotone/visy_vision_system/wiki/Step-3:-Groundwork).

[***>>>visy system image<<<***](https://1drv.ms/u/s!Ak6d5NrNShMWbGWBAE_wLZKFaYs?e=Y8fECA)

# Visy assembly

The visy vision system is designed as a kit. You have to do some assembly steps on your own. The following pages guide you to all assembly steps including pictures and information. Check your tools and parts first and if it's all there take some time (about 4 hours) to build the system. Let's start this practical, educational and interesting experience.

***How to build your visy?*** No worrys we create a wiki...

Wiki: [>>>How to build you visy<<<](https://github.com/deltarobotone/visy_vision_system/wiki)

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(35).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(35).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(36).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(36).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(50).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(50).PNG)

# Visy assembly clip

coming soon...

# Electronics

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_parts/visy_parts%20(27).PNG" width="400">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_parts/visy_parts%20(27).PNG)

[>>>Partlist<<<](https://github.com/deltarobotone/visy_vision_system/wiki/Step-2:-Check-your-parts)

[>>>Files<<<](https://github.com/deltarobotone/visy_vision_system/tree/master/io_board)

***How to get the board?*** No problem...

...we uploaded our board to the aisler.com page. So you only have to follow this link and create an account to order the board for a good price.

Shop link: [>>>Visy IO Board<<<](https://aisler.net/p/KVFINYWA)

***How to get the parts?*** All of this are standard parts...

- You can check your own maker stock first ;)
- Use the partlist on the link above and check the recommended shops
- A lot of shops and maybe your school or university have this parts availible

# Case

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_parts/visy_parts%20(15).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_parts/visy_parts%20(15).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_parts/visy_parts%20(16).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_parts/visy_parts%20(16).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(59).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(59).PNG)

[>>>Files<<<](https://github.com/deltarobotone/visy_vision_system/tree/master/case)

***How to get the parts?*** No problem...

...we tested [i.materialise.com](http://i.materialise.com/) and created some shop items so you can easily order the required parts using this links:

[>>>Visy Case Base<<<](https://i.materialise.com/de/shop/item/visy-case-base)

[>>>Visy Case Middle<<<](https://i.materialise.com/de/shop/item/visy-case-middle)

[>>>Visy Case Top<<<](https://i.materialise.com/de/shop/item/visy-case-top)

You can try your own 3D-Printer but we did not test any FDM printer yet.

# User-Interface

We build an simple user interface for the touch display on the backside of visy system. The user interface starts automatically after every reboot. It is possible to close the interface using the "X" button. By default it is possible to start and stop the sorting application. 

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_doc/visy_doc%20(5).PNG" width="400">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_doc/visy_doc%20(5).PNG)

With the arrows you can change the displayed image processing state. At this time we included the detected image with coloured lines around conveyor/metalchips. This is the last step at image processing using find contours algorithm. After that first image follows the raw image and some image processing states like hsi, chroma and threshold for binarization. So it is possible to have a look behind the scenes of image processing. 

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_doc/visy_doc%20(8).PNG" width="400">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_doc/visy_doc%20(8).PNG)

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_doc/visy_doc%20(11).PNG" width="400">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_doc/visy_doc%20(11).PNG)

Note: The system detects the conveyor system realy slow because it uses the complete image. After that only the cropped conveyor system is used to detect the metal chips.

The last button in row activates the update script. It is neccessary to connect the system to the internet using wifi or cable. 
Note: The systems gets the latest commits from master branches on github

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_doc/visy_doc%20(13).PNG" width="400">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_doc/visy_doc%20(13).PNG)

# The full system

In the first way visy is designed to extend the Deta-Robot Ine project to push it to the next level. In combination with Delta-Robot One and the conveyor system visy could do it's predifined jobs:

- Detect conveyor system
- Control conveyor system
- Detect metalchips (velocity, colour, etc.)
- Control Delta-Robot One (grasp planner, pick and place)
- Sort metalchips by colour

You can have a look a the other projects using the links below.

- [Delta-Robot One](https://github.com/deltarobotone/how_to_build_your_robot)
- [Conveyor System](https://github.com/deltarobotone/conveyor_system)

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/full_system_orange/full_system_orange%20(1).PNG" width="400">](https://raw.githubusercontent.com/deltarobotone/image_database/master/full_system_orange/full_system_orange%20(1).PNG)

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/full_system_orange/full_system_orange%20(3).PNG" width="400">](https://raw.githubusercontent.com/deltarobotone/image_database/master/full_system_orange/full_system_orange%20(3).PNG)

# ROS workspace

All visy software parts are developed using ROS. We provide software modules called packages in ROS so you could use some of them at your own application. For details have a look at the packages readme files using the links below. On the following picture you see the ROS workspace of visy system.

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_doc/visy_doc%20(1).PNG" width="1000">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_doc/visy_doc%20(1).PNG)

- [visy_sorting_app_pkg](https://github.com/deltarobotone/visy_sorting_app_pkg)
- [visy_detector_pkg](https://github.com/deltarobotone/visy_detector_pkg)
- [visy_user_interface_pkg](https://github.com/deltarobotone/visy_user_interface_pkg)
- [one_easy_protocol_pkg](https://github.com/deltarobotone/one_easy_protocol_pkg)
- [visy_neopixel_pkg](https://github.com/deltarobotone/visy_neopixel_pkg)
- [raspicam_node](https://github.com/UbiquityRobotics/raspicam_node)

# Software module usage

Visy is developed as a modular system. If you only want to use the lightring/statusbar at visy_neopixel_pkg and the camera_node you can deactivate all other packages of visy system with simple command in terminal. Not: If you deactivate the detector package the camera is also deactivated. Use your own launch file or the launch files provided by [raspicam_node](https://github.com/UbiquityRobotics/raspicam_node) package we installed on visy.

Deactivate visy packages:
```
sudo systemctl disable launchNeopixel
sudo systemctl disable launchDetector
sudo systemctl disable launchUserInterface
sudo systemctl disable launchSortingApp
```
Activate visy packages:
```
sudo systemctl enable launchNeopixel
sudo systemctl enable launchDetector
sudo systemctl enable launchUserInterface
sudo systemctl enable launchSortingApp
```

### Next steps

We are working for more then 2 years on this project after university or work. Because of that we are a bit late lokking at ubuntu, ros and the Raspberry itself. If a few people like this project this means contributing, give stars or donate we will update the project with following points at first.

- [ ] Update case for Raspberry Pi 4
- [ ] Update ubuntu to focal 20.04
- [ ] Update ROS to noetic
- [ ] Install tensorflow or pytorch
- [ ] Change detectors from opencv to a neural network

# Social Media

Instagram: @deltarobotone #deltarobotone

Facebook: Deltarobotone

Youtube: [deltarobotone](https://www.youtube.com/channel/UCeqy13LiwtQ1QQTYZzzyFRA)

# Video gallery 

coming soon...

# Image gallery

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(57).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(57).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(58).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(58).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(59).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(59).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(60).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(60).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(61).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(61).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(62).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(62).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(63).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(63).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(65).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_assembly/visy_assembly%20(65).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_holder/visy_holder%20(19).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_holder/visy_holder%20(19).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_holder/visy_holder%20(20).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_holder/visy_holder%20(20).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_holder/visy_holder%20(21).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/visy_holder/visy_holder%20(21).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/full_system_orange/full_system_orange%20(1).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/full_system_orange/full_system_orange%20(1).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/full_system_orange/full_system_orange%20(2).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/full_system_orange/full_system_orange%20(2).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/full_system_orange/full_system_orange%20(3).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/full_system_orange/full_system_orange%20(3).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/full_system_orange/full_system_orange%20(4).PNG" width="200">](https://raw.githubusercontent.com/deltarobotone/image_database/master/full_system_orange/full_system_orange%20(4).PNG)

# Copyright Notice

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

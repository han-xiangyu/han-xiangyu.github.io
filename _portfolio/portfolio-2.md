---
title: "Tello UAV Control"
excerpt: "This project aims to using flight simulator to control a Tello UAV remotely.
<br/><img src='/images/UAV.png'>"
collection: portfolio
---
## Source Code
Learn about [the project in GitHub](https://github.com/han-xiangyu/Avengers-Face-Detection).

## Video
Here is the [project demonstration](https://youtu.be/2pcbGjhW9ik).

## Description
This project aims to using flight simulator to control a Tello UAV remotely.

Communicating with the Tello drone can be done either using official Tello SDK or one of the unofficial libraries. The unofficial libraries originated from the reverse-engineering the raw packages broadcasted by the Tello. This ROS package is build on top of the unofficial TelloPy library. The TelloPy library is used at this moment since it offers more functionalities than the official Tello SDK or any other unofficial library.

Developing of the tello_driver ROS package is inspired by tello_driver, which by now diverged considerately from the original work. Furthermore, development of this ROS package pursues not to modify the TelloPy library, but instead apply any modification or addition to the ros_driver package in an encapsulated manner. This prevents breaking functionalities when updating the TelloPy library.

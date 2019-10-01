---
layout: archive
lang: en
ref: getting_started
read_time: true
share: true
author_profile: false
permalink: /docs/en/platform/turtlebot3/getting_started/
sidebar:
  title: TurtleBot3
  nav: "turtlebot3"
product_group: turtlebot3
page_number: 5
---

<div style="counter-reset: h1 4"></div>

# [Getting Started](#getting-started)
This page is for users who are new to TurtleBot3. The manual has an enormous amount of content, but this page explains how information is divided.

## [About TurtleBot3](#about-turtlebot3)
First of all, collect information from the [Overview][overview], [Notices][notices], [Features][features], and [Specifications][specifications] pages to get an overall understanding of TurtleBot3.

![](/assets/images/platform/turtlebot3/hardware_setup/turtlebot3_models_800.png)

## [First steps for using TurtleBot3](#first-steps-for-using-turtlebot3)
**WARNING**: Make sure to follow either of Setup guide (**ROS** or **ROS 2**). Otherwise, it may cause unexpected issue. 
{: .notice--warning}
When you have enough understanding about TurtleBot3 from above step, here are the software and hardware setups. Be aware that it is a time-saver to set up the SBC and your PC first, rather than assembling the robot. It is recommended to proceed in the following order.

1. **PC Setup**
- Install Linux, ROS and application software for TurtleBot3 on your **Remote PC**.
2. **SBC Setup**
- Install Linux, ROS and hardware related software to control the TurtleBot3 on your **TurtleBot PC**.
3. **OpenCR Setup**
- Upload latest firmware of TurtleBot3 to OpenCR embedded board.
4. **Hardware Setup**
- Assemble TurtleBot3 by follwing an **Assembly Manual**. Be sure to setup the SBC and OpenCR before assembling the robot.

**TIP** : If you want to use other products instead of SBCs and Sensors included in the TurtleBot3 package, please refer to the [Compatible Devices][compatible_devices] page.
{: .notice--success} 

![](/assets/images/platform/turtlebot3/setup/setup.png)

### Related Documents
**ROS** :
- [PC Setup][pc_setup_ros]
- [SBC Setup][sbc_setup_ros]
- [OpenCR][opencr_setup_ros]
- [Hardware Setup][hardware_setup]

**ROS 2** :
- [PC Setup][pc_setup_ros2]
- [SBC Setup][sbc_setup_ros2]
- [OpenCR][opencr_setup_ros2]
- [Hardware Setup][hardware_setup]


## [Let's try the basic operation](#lets-try-the-basic-operation)
Once you have completed the above steps, run the robot through the provided **Bringup** package, and remotely move the robot with the teleoperation feature.  
Next, let's check various sensors' value mounted on the robot or learn how to control the robot by reading **Basic Operation** page.

![](/assets/images/platform/turtlebot3/example/operation.png)

### Related Documents
**ROS** :
- [Bringup][bringup_ros]
- [Basic Operation][basic_operation_ros]

**ROS 2** :
- [Bringup][bringup_ros2]
- [Basic Operation][basic_operation_ros2]

## [Keep TurtleBot3's various technologies with you](#keep-turtlebot3s-various-technologies-with-you)
The TurtleBot3’s core technology is **SLAM**, **Navigation** and **Manipulation**, making it suitable for home service robots. These technologies can be applied either on a real robot or a virtual robot with **Simulation** feature.  
Of course, they can be implemented in TurtleBot3, such as **Autonomous Driving** and **Machine Learning**. In addition, we are introducing 12 different types of **Locomotion** as TurtleBot3 Friends, as well as differential drive mobile robot. With this openended component, handful of TurtleBot3 friends with various characteristics could be built. You can create a totally new robot that is never seen before. Also interesting applications such as Follower Demo, Panoramic Demo, and Automatic Parking are available. See **Applications** page for more application examples.

![](/assets/images/platform/turtlebot3/example/technologies.png)

### Related Documents
**ROS** :
- [SLAM][slam]
- [Navigation][navigation]
- [Simulation][simulation]
- [Manipulation][manipulation]
- [Autonomous Driving][autonomous_driving]
- [Machine Learning][machine_learning]
- [Locomotion][locomotion]
- [Applications][applications]

**ROS 2** :
- [SLAM][slam_ros2]
- [Navigation2][navigation2_ros2]
- [Simulation][simulation_ros2]

**NOTE** : Various contents of ROS 2 will be released soon.
{: .notice}

## [Learn and Explore more](#learn-and-explore-more)
The above are just a few examples of using TurtleBot3. You can learn more and challenge yourself with the following information.

You can **Learn** more through the ROS courses provided by the Construct, the various lectures created by TurtleBot3 users, web content, YouTube courses, free books, and more. In addition, various **Videos** produced by ROBOTIS will be helpful, and use cases using TurtleBot3 can be checked through various **Projects** released by TurtleBot3 research collaborators and TurtleBot3 users. You can also try a variety of challenges through **Challenges**.

![](/assets/images/platform/turtlebot3/example/projects.png)

### Related Documents
- [Learn][learn]
- [Videos][videos]
- [Projects][projects]
- [Challenges][challenges]

## [References and Contacts](#references-and-contacts)
The [Appendixes][appendixes] contains information on components used in TurtleBot3 such as DYNAMIXEL, OpenCR and LDS. The open source used by TurtleBot3 is listed on [OpenSource and Licenses][opensource_and_licenses] page and this page contains information about each license. If you have any questions about TurtleBot3, please refer to our [FAQ][faq] or leave your [Contact information][contact_us].

### Related Documents
- [Appendixes][appendixes]
- [OpenSource and Licenses][opensource_and_licenses]
- [FAQ][faq]
- [Contact US][contact_us]

[overview]: /docs/en/platform/turtlebot3/overview/
[notices]: /docs/en/platform/turtlebot3/notices/
[features]: /docs/en/platform/turtlebot3/features/
[specifications]: /docs/en/platform/turtlebot3/specifications/

[getting_started]: /docs/en/platform/turtlebot3/getting_started/

[setup]: /docs/en/platform/turtlebot3/setup/
[pc_setup_ros]: /docs/en/platform/turtlebot3/pc_setup/
[pc_setup_ros2]: /docs/en/platform/turtlebot3/ros2_setup/
[sbc_setup_ros]: /docs/en/platform/turtlebot3/sbc_setup/
[sbc_setup_ros2]: /docs/en/platform/turtlebot3/ros2_setup/#sbc-setup
[opencr_setup_ros]: /docs/en/platform/turtlebot3/opencr_setup/
[opencr_setup_ros2]: /docs/en/platform/turtlebot3/ros2_setup/#opencr-setup
[hardware_setup]: /docs/en/platform/turtlebot3/hardware_setup/
[compatible_devices]: /docs/en/platform/turtlebot3/compatible_devices/

[bringup_ros]: /docs/en/platform/turtlebot3/bringup/
[basic_operation_ros]: /docs/en/platform/turtlebot3/basic_operation/
[bringup_ros2]: /docs/en/platform/turtlebot3/ros2_bringup/
[basic_operation_ros2]: /docs/en/platform/turtlebot3/ros2_basic_operation

[slam]: /docs/en/platform/turtlebot3/slam/
[navigation]: /docs/en/platform/turtlebot3/navigation/
[simulation]: /docs/en/platform/turtlebot3/simulation/
[manipulation]: /docs/en/platform/turtlebot3/manipulation/
[autonomous_driving]: /docs/en/platform/turtlebot3/autonomous_driving/
[machine_learning]: /docs/en/platform/turtlebot3/machine_learning/
[locomotion]: /docs/en/platform/turtlebot3/locomotion/
[applications]: /docs/en/platform/turtlebot3/applications/

[slam_ros2]: /docs/en/platform/turtlebot3/ros2_slam/
[navigation2_ros2]: /docs/en/platform/turtlebot3/ros2_navigation2/
[simulation_ros2]: /docs/en/platform/turtlebot3/ros2_simulation/

[learn]: /docs/en/platform/turtlebot3/learn/
[videos]: /docs/en/platform/turtlebot3/videos/
[projects]: /docs/en/platform/turtlebot3/projects/
[challenges]: /docs/en/platform/turtlebot3/challenges/

[appendixes]: /docs/en/platform/turtlebot3/appendixes/
[opensource_and_licenses]: /docs/en/platform/turtlebot3/opensource/
[faq]: /docs/en/platform/turtlebot3/faq/
[contact_us]: /docs/en/platform/turtlebot3/contact_us/

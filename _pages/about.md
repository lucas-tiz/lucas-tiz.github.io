---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a PhD candidate in the [Adaptive Robotic Manipulation Lab](https://armlab.gatech.edu/) at Georgia Tech. I enjoy working on mechatronic system design & control, embedded software, and robots in general.



Projects
======
Below are several projects I've worked on as part of my research, for coursework, or just for fun.

Jumping robot trajectory optimization<a name="jumping-robot"></a>
------
In this project, we planned jumps for a pneumatic muscle--driven legged robot. We implemented direct collocation with hybrid robot dynamics (robot feet on vs. off ground) using the [GTSAM factor graph library](https://gtsam.org/). We used a soft model to approximate the hybrid pressure dynamics (valves open vs. closed), in which time-shifted sigmoids 'activate' or 'deactivate' each set of pressure dynamics based on valve state.

{% include youtube-player.html id="VnW4Kd7cc7Q" %}



Optical sensor design for pneumatic muscle state estimation<a name="optical-sensor"></a>
------
I developed a 'pneumatic artificial muscle' actuator with integrated optical sensors for estimation of muscle contraction and force. Each optical sensor uses an LED-photodiode pair to measure the light reflected by a silicone diaphragm embedded in the muscle.

{% include youtube-player.html id="-PgJ--pesHY" %}



Particle filter for 2D robot localization<a name="particle-filter"></a>
------
I implemented a particle filter for localizing a robot inside a building---a map of the building is given, but there is no prior knowledge of robot pose. I develped motion and sensor models for robot odometry and LIDAR data, used ray-casting to determine true range measurements, and performed importance sampling to resample particles at each timestep.

{% include youtube-player.html id="p8gdNsmijZA" %}



Balancing wheel<a name="balance-wheel"></a>
------
For this project, affectionately called the 'hamster wheel,' we built a two-wheeled system in which a free wheel is balanced on top of a motor-driven base wheel. The system is linearized around the free wheel's top position and an LQR controller is implemented.

{% include youtube-player.html id="xTCCFgi41Hs" %}



Balancing robot<a name="balance-bot"></a>
------
I built a simple balancing robot driven by two DC gearmotors with encoders. An IMU was used to estimate robot orientation via a complementary filter. Similar to the balancing wheel above, an LQR controller was implemented on an MSP432 microcontroller.

{% include youtube-player.html id="88t78ZqRikY" %}



<!-- Gaussian process regression for 2-DOF arm
------

Knee exoskeleton assistance timing optimization
------ -->

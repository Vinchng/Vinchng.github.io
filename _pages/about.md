---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm a MSc student from [Mechanical Automation Engineering](https://www4.mae.cuhk.edu.hk/), [The Chinese University of Hong Kong](https://www.cuhk.edu.hk/english/index.html). My research interest includes robotics, robot manipulator, artificial intelligence and control.

You can find my CV here: [Li's Curriculum Vitae](../assets/NewCV_LJC.pdf).

[Email: jinchengli0315@gmail.com](mailto:jinchengli0315@gmail.com)

# 📖 Educations
Mechatronics Modeling & Simulation
- *Aug 2024 – Present*. [The Chinese University of Hong Kong](https://www4.mae.cuhk.edu.hk/), Hong Kong, CN
  - MSc. in Mechanical Automation Engineering, **GPA: 3.54/4.00**
  - Courses: Robotics Studio, Reinforcement Learning, Control, Intro to Robotics

- *Aug 2023 - Jun 2024*. [University of Detroit Mercy](https://www.udmercy.edu/), Detroit, MI, US
  - B.E. in Mechatronics, Robotics, and Automation Engineering, **GPA: 3.91/4.00**
  - Courses: Robotics, Autonomous Mobility Robotics, Embedded Systems, Computational Intelligence Technique

- *Sept 2020 - Jun 2024*. [Beijing University of Chemical Technology](https://english.buct.edu.cn/main.htm), Beijing, CN
  - B.E. in Mechanical Design, Manufacturing and Automation, **GPA: 3.33/4.33**
  - Courses: Automatic Control Design, Artificial Intelligence, Mechine Design, Program Design, Hydraulic and Atmospheric Pressure Transmission 

# 📝 Publications 

[Working principle and application analysis of UART](https://ieeexplore.ieee.org/document/10090571)

**Jincheng Li**, Jianfeng Chen, Lehan Cao 
**ICEMA-2022**

# 🚀 Projects
<div class='paper-box'>
  <div class='paper-box-image' style="display: flex; align-items: flex-start; gap: 10px;">
    <div class="badge" style="align-self: flex-start;">Bruce Robot</div>
    <img src='images/Bruce.gif' alt="sym" style="width: 45%; height: auto;">
    <img src='images/Bruce_Gazebo.gif' alt="sym" style="width: 45%; height: auto;">
  </div>
  <div class='paper-box-text' markdown="1">

**Balance Control and Motion Design for the Bruce Bipedal Robot**

- Successfully implemented stable bipedal standing, walking, squatting, and jumping for the Bruce robot.
- Applied QP (Quadratic Programming)-based control to maintain dynamic balance during motion execution and center-of-mass (CoM) transitions.
- Developed mid-level control code for task-specific CoM trajectory planning and execution of robotic movements.
- Designed user-facing high-level code to interpret input commands, enabling real-time robot control and seamless task switching.

</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
  <div>
    <div class="badge">Cart-Pole</div>
    <img src='images/LQR_Pendulum.gif' alt="sym" width="100%">
  </div>
  </div>
<div class='paper-box-text' markdown="1">

**Simscape Simulation of the Cart-Pole Model**

- Built a classic Cart-Pole model for the inverted pendulum system using MATLAB Simulink and Simscape Multibody.
- Developed a physical model of the entire inverted pendulum system and extracted the characteristic matrix.
- Designed a controller using the LQR algorithm to stabilize the cart at the origin.

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
  <div>
    <div class="badge">Senior Project</div>
    <img src='images/SeniorProject.gif' alt="sym" width="100%">
  </div>
  </div>
<div class='paper-box-text' markdown="1">

**Indoor Assistive Robot System**

- Co-developed an indoor assistive robot system integrating computer vision, robotic arm grasping, and multi-target navigation. The system understood user needs via voice interaction, recognized target objects in real-time, grasped them, and delivered them to users.
- Used Pioneer 3DX as the platform, employed the move_base package for navigation, Microsoft Azure for voice interaction, Kinect v2 and YOLOv8 for object recognition, and the Trossen RX200 robotic arm with MoveIt for arm training and grasping.
- Responsible for multi-target navigation: configured the global and local planners in move_base, tuned Gmapping and costmap parameters, implemented an A*-based multi-target navigation node, and developed communication nodes for arm and vision modules.

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
  <div>
    <div class="badge">Cable Robot</div>
    <img src='images/cable_robot.gif' alt="sym" width="100%">
  </div>
  </div>
<div class='paper-box-text' markdown="1">

**2D Cable Driven Robot**

- Co-developed an indoor assistive robot system integrating computer vision, robotic arm grasping, and multi-target navigation. The system understood user needs via voice interaction, recognized target objects in real-time, grasped them, and delivered them to users.
- Used Pioneer 3DX as the platform, employed the move_base package for navigation, Microsoft Azure for voice interaction, Kinect v2 and YOLOv8 for object recognition, and the Trossen RX200 robotic arm with MoveIt for arm training and grasping.
- Responsible for multi-target navigation: configured the global and local planners in move_base, tuned Gmapping and costmap parameters, implemented an A*-based multi-target navigation node, and developed communication nodes for arm and vision modules.

</div>
</div>

# 🎖 Honors and Awards
- *2023.02* Beijing University of Chemical Technology Single-Item Scholarship


# 🧠 Skills
- **Language Skill:** Fluent in English listening and speaking, capable of seamless daily communication.
- **Programming Language:** Profecient in Python, C++, Matlab. Especially in Robotics.
- **Microcontroller Applications:** Proficient in using Texas Instruments TM4C series, STM32 series, 89C52 microcontroller, and Arduino.
- Proficient in using Raspberry Pi 4B for Linux development.


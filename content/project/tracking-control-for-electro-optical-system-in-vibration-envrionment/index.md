---
title: Tracking control for Electro-Optical system in Vibration envrionment
date: 2022-06-25T12:22:24.389Z
draft: false
featured: false
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
---
1. Summary of the project:

   Electro-optical system (EOTs) is the system used in Military to track moving objects. The important requirement of the EOTSs is that the system must be accurately pointed to a fixed or moving target even if operating in vibration environment such as ship, air plane, tank. To achieve this task is not simple because of the disturbances affecting the operating of EOTS. The disturbances affecting the operating of EOTS are the disturbance torque because of angular motion of the base body (when EOTS works in vibration environment), cross-coupling effect between the pitch and yaw channel and so on.

   In this project, I and my partner proposed and implemented some modern and efficient control algorithms such as self-tuning Fuzzy PID, self-tuning fuzzy sliding mode to help the EOTs precisely track the moving targets. 

   ![](tracking_control.png "The proposed self-tuning fuzzy sliding mode control architecture")

   This project is the project of Vietnam Academic of Science and Technology. Thus, I cannot share the code

   You can read our publication at: https://vjs.ac.vn/index.php/jcc/article/view/12931/103810383012
2. Technologies and Programming languages used: Matlab, C++
3. Main responsibilities: Research to propose the algorithms, Conduct the experiments by simulation and reality, Implementation
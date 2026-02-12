LEGO-inspired Modular Platform for Reconfigurable and Intelligent Soft Electronics
Status: Under Revision
Journal

📝 Overview
This repository contains the source code, datasets, and hardware design files associated with our paper titled "LEGO-inspired modular platform for reconfigurable and intelligent soft electronics", which is currently under revision for submission to Science China-Technological Sciences.

Abstract
Soft electronics are well-suited for wearable systems due to their ability to conform to the human body. However, most existing designs are built for specific tasks and lack flexibility for reuse or expansion. Here, we develop a modular soft-electronic platform that connects sensing, control, actuation, and power modules through a flexible version of the Controller Area Network (CAN) bus. Each module has a defined function and can be added, removed, or replaced without changing the rest of the system. We apply the platform in two representative scenarios: a static pressure-mapping insole and a dynamic limb-mounted motion recognition system. The insole integrates a 32-channel pressure sensor grid for high-resolution plantar load monitoring during postural tasks. When adhered onto the thigh and/or shank, the system leverages inertial sensing and an onboard Long Short-Term Memory (LSTM)-Convolutional Neural Network (CNN) model to classify seven daily activities with real-time feedback. These demonstrations showcase the platform’s adaptability across static and dynamic use cases, offering a solution toward reconfigurable, intelligent soft electronics for wearable and interactive applications.

Keywords: modular soft electronics, CAN bus communication, motion sensing, human activity recognition

✨ Key Features
Modular Architecture: A LEGO-inspired design allowing for flexible assembly and disassembly of functional units.
Robust Communication: Implementation of a flexible CAN bus protocol for reliable inter-module data transmission.
Embedded AI: Integration of LSTM-CNN models directly on the edge device for real-time activity recognition.
Versatile Application: Validated in both static pressure mapping (insole) and dynamic motion sensing (limb-mounted).

🧪 Demonstration Scenarios
1. Static Pressure-Mapping Insole
Hardware: 32-channel pressure sensor grid.
Application: High-resolution plantar load monitoring.
Use Case: Postural task analysis.
2. Dynamic Limb-Mounted Motion Recognition
Hardware: Inertial sensors (IMU) mounted on thigh/shank.
Algorithm: Onboard LSTM-CNN hybrid model.
Capability: Classification of 7 daily activities with real-time feedback.

👥 Authors & Affiliations
DaPeng Wang*, YaHui Li*, MingYuan Wang, HaoZhe Wen, BingTian Han, ShiJi Yuan, ChuiZhou Meng*, Teng Liu*, ShiJie Guo, and YuanJin Zheng*

*Equal contribution / Corresponding authors

Affiliations:

1.Engineering Research Center of Ministry of Education for Intelligent Rehabilitation Device and Detection Technology, Tianjin, 300401, P. R. China
2.Hebei Key Laboratory of Smart Sensing and Human-Robot Interaction, School of Mechanical Engineering, Hebei University of Technology, Tianjin 300401, P. R. China
3.School of Mechanical Engineering, Hebei University of Technology, Tianjin 300401, P. R. China
4.School of Electrical and Electronic Engineering, Nanyang Technological University, Singapore, 639798, Singapore
5.Research Institute of Wearable Electronic Materials & Devices, School of Materials Science & Engineering, Zhejiang Sci-Tech University, Hangzhou 310018, P. R. China
6.School of Interdisciplinary Science, Beijing Institute of Technology, Beijing, 100081, P. R. China

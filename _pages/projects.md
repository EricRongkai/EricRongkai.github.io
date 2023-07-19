---
layout: archive
title: "Projects & Reseach"
permalink: /projects/
author_profile: true
---

## 1. Non-invasive soft body-machine interface

<br>
<div>			 <!--块级封装-->
     <center>
     <img src="/images/TNSRE.jpg"
          alt="Failed load figure"
          width="300"/> 
     <img src="/images/TNSRE_2.jpg"
      alt="Failed load figure"
      width="595"/>
      <br>
      <img src="/images/TNSRE.gif"
      alt="Failed load figure"
      width="447"/>
      <img src="/images/TNSRE_2.gif"
      alt="Failed load figure"
      width="447"/>
     </center>
</div>
<br>

### ***Background:***
  Spinal cord injury (SCI) occurring in the cervical region of the spine can result in tetraplegia, a condition where the patient suffers a significant decrease in functionality or complete loss of independent movement in both their arms and legs. Most of tetraplegics end up partially or completely dependent on their caregivers. Because of the weak hand grip, they cannot use joystick stably for a long time. Customized human-machine interfaces for controlling assistive devices are essential for improving patient self-help and reducing the burden of social care.

### ***Contribution:*** 
   - Developed a body-machine interface that utilizes capacitive soft strain sensor arrays and IMUs to capture residual shoulder motion in patients with SCI. <br>
   - Designed the online parsing, calibration, and data visualization interfaces of the interactive interface data, and built a virtual simulation environment for wheelchair manipulation based on Unity3D. <br>
   - Proposed a shared control-based data decoding method that allows for online intervention of the user's intention inference.

<br>

## 2. Knee exoskeleton robot for gait symmetry rehabilitation

<br>
<div>			 <!--块级封装-->
     <center>
     <img src="/images/RAL.jpg"
          alt="Failed load figure"
          width="375"/> 
     <img src="/images/RAL.gif"
      alt="Failed load figure"
      width="530"/>
      <br>
      <img src="/images/EXO_1.jpg"
      alt="Failed load figure"
      width="238"/>
      <img src="/images/EXO_2.png"
      alt="Failed load figure"
      width="238"/>
      <img src="/images/EXO_3.png"
      alt="Failed load figure"
      width="420"/>
     </center>
</div>
<br>

### ***Background:***
  In the acute phase of stroke, nearly 70% of patients have a walking impairment. Even with rehabilitation and spontaneous recovery, 50% of hemiplegic patients cannot walk independently. The reduced walking ability increases patients' risk of secondary injury and seriously affects their quality of life. Gait symmetry recovery is a major rehabilitation objective of stroke patients.
### ***Contribution:*** 
  - Developed a knee exoskeleton robotic system (Maxon EC90 Flat Motor, Harmonic 50:1 Reducer, Maxon Escon 50/5 Driver, Dual Encoder, Torque Sensor). <br>
  - Multimodal human motion information acquisition and robot control system based on AMQP protocol. <br>
  - Based on the adaptive nonlinear frequency oscillators (ANFO) and movement primitive, we encode the knee joint trajectory of the unaffected side into a low-dimensional space according to the real-time gait phase.<br>
  - A probabilistic form of robot gait skill library for providing machine strategies is constructed by collecting standard gait data. <br>
  - Online disambiguation and fine-tuning of user-unaffected side inputs to improve robot system safety based on a shared autonomy framework.
<br>

## 3. Inertial Human Motion Capture System

<br>
<div>			 <!--块级封装-->
     <center>
     <img src="/images/IEEE Sensors_3.png"
          alt="Failed load figure"
          width="560"/> 
     <img src="/images/MOCAP_2.jpg"
      alt="Failed load figure"
      width="335"/>
     <br>
     <img src="/images/MOCAP.gif"
          alt="Failed load figure"
          width="485"/> 
     <img src="/images/IEEE Sensors_2_COMP.gif"
      alt="Failed load figure"
      width="408"/>
     </center>
</div>
<br>

### ***Background:***
  Human motion capture systems based on inertial sensors often require the placement of sensor nodes on each set of active limbs, which significantly increases the deployment cost of motion capture devices. In this study, we consider the motion of a multilink complex system such as the human body to be redundant. Therefore based on an inertial motion capture system developed in-house, we investigate the possibility of using sparse nodes for 3D motion reconstruction.
  
### ***Contribution:*** 
  - Hardware and software development of inertial motion capture devices <br>
  - Developed algorithms for avatar pose solving of upper body and lower limbs. <br>
  - Deploied a standard inertial sensor-based node to collect a large amount of human lower limb motion data to construct a gait motion database. <br>
  - By training an LSTM network model with sparse sensor inputs to dense sensor inputs, we achieved full lower limb joint pose reconstruction using only three sensor nodes.
<br>

## 4. Quantitative evaluation of movement disorders in Parkinson's disease

<br>
<div>			 <!--块级封装-->
     <center>
     <img src="/images/Parkinson.gif"
          alt="Failed load figure"
          width="297"/> 
     <img src="/images/Parkinson_2.gif"
          alt="Failed load figure"
          width="297"/>
     <img src="/images/Parkinson_3.gif"
          alt="Failed load figure"
          width="297"/> 
     </center>
</div>
<br>

### ***Background:***
 Parkinson's disease is a degenerative neurological disorder that impacts motor abilities. Individuals with this condition frequently experience symptoms such as resting tremor, bradykinesia, rigidity, postural instability, and abnormal posture and gait. Parkinson's disease often requires a complex medication regimen, involving multiple drugs and strict adherence to specific schedules. The Parkinson's Chronic Disease Management System has the potential to aid physicians in diagnosis and support patients in their medication regimen. 
### ***Contribution:*** 
  - Designed a wearable synchronous data acquisition system that can realize multiple IMU signals, EMG signals, and video signals. <br>
  - Wireless uploading of collected data locally or in the cloud is realized based on BLE and NB-IoT.<br>
  - The developed system was used to collect motor information from 70 typical Parkinson's patients in the Department of Neurology of Peking Union Medical College Hospital.<br>
  - Quantitative assessment of gait impairment and locomotor ability and detection of abnormal gait in Parkinson's patients realized based on RBF-SVM.
<br>

## 5. Virtual reality training system and hardware design for uppper limb rehabilitation robots

<br>
<div>			 <!--块级封装-->
     <center>
     <img src="/images/2DOFEXO.png"
          alt="Failed load figure"
          width="295"/> 
     <img src="/images/5DOFEXO (2).png"
          alt="Failed load figure"
          width="310"/>
     <img src="/images/5DOFEXO.png"
          alt="Failed load figure"
          width="290"/> 
     </center>
</div>
<div>			 <!--块级封装-->
     <center>
     <img src="/images/image049.jpeg"
          alt="Failed load figure"
          width="306"/> 
     <img src="/images/image050.png"
          alt="Failed load figure"
          width="110"/> 
     <img src="/images/Wrist_2.gif"
          alt="Failed load figure"
          width="475"/>
     </center>
</div>
<br>

### ***Contribution:*** 
  - Development and debugging of an embedded system for communication and motion control of a five-degree-of-freedom exoskeleton upper limb rehabilitation robot. <br>
  - Development of virtual reality rehabilitation training systems based on Unity3D for 6-DOF and 2-DOF upper limb rehabilitation robots.
<br>
    
























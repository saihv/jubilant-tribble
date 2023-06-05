---
layout: page
title: Research
---

### Large Language Models for Robotics
![](https://www.microsoft.com/en-us/research/uploads/prod/2023/02/chatgpt_robotics_gif.gif)

Current robotics pipelines require specialized engineers in the loop writing code specific to each task or form factor. 
LLMs such as ChatGPT unlock a new robotics paradigm, allowing a (potentially non-technical) user to sit on the loop, providing high-level feedback to the large language model while monitoring the robot’s performance. In this research, we extended the capabilities of ChatGPT to robotics, and controlled multiple platforms such as robot arms, drones, and home assistant robots intuitively with language.

---

### Data-driven Sensor Simulation for Realistic LiDARs
![](https://www.microsoft.com/en-us/research/uploads/prod/2022/09/Screen-Shot-2022-09-27-at-10.15.46-AM-1536x1099.png)

While present simulations can generate high quality camera imagery, when it comes to non-visual classes of sensors, they often fall back upon simplified models. Complex sensors such as LiDAR, which lie at the heart of a majority of present day autonomous systems such as self-driving cars, are challenging to model given their dependence on aspects such as material properties of all the objects in an environment. Our data-driven sensor simulation framework uses generative models to emulate LiDAR point clouds given only RGB data.

---

### Representation Learning and Reinforcement Learning for Event Cameras
![](https://www.microsoft.com/en-us/research/uploads/prod/2021/03/1400x788_AirSim_noLogo.gif)

Event-based cameras are dynamic vision sensors that can provide asynchronous measurements of changes in per-pixel brightness at a microsecond level. This makes them significantly faster than conventional frame-based cameras, and an appealing choice for high-speed navigation. While an interesting sensor modality, this asynchronous data poses a challenge for common machine learning techniques. This work introduces an event variational autoencoder for unsupervised representation learning from asynchronous event camera data, and subsequently a reinforcement learning pipeline to apply event camera data to navigation.

---

### Uncertainty-aware Planning for Micro Aerial Vehicle Swarms
![](http://www.saihv.com/images/coplan.png)

In this project that forms the second part of my PhD thesis, I investigated the idea of collaborative uncertainty-aware path planning for vision based micro aerial vehicles. For vehicles that are equipped with cameras and can localize collaboratively (see below), this framework captures the estimated "quality" of localization from various viewpoints. Evolutionary algorithms were integrated with an RRT based path planning framework to result in plans which allow the vehicles to navigate intelligently towards areas that can improve their vision based localization accuracy: such as moving only in well-lit locations, observing texture-rich objects, building denser maps before navigating etc.  

---

### Collaborative Localization for Micro Aerial Vehicle Swarms
![](http://www.saihv.com/images/cl.png)

As the first part of my PhD thesis, I developed a collaborative localization pipeline that is applicable for a swarm of multirotor aerial vehicles with each vehicle using a monocular camera as its primary sensor. Images are captured continuously from each vehicle and used for reconstruction of the surrounding environment. This sparse reconstruction is then used by the vehicles for individual localization in a decentralized fashion, along with on-demand relative localization between vehicles. A covariance-intersection based approach enables robust fusion of individual and relative poses for overall accuracy.

---

### Drone Detection through Depth Images
![](http://www.saihv.com/images/drdet.png)

A specific advantage of depth sensing versus other detection methods is that a depth map is able to directly provide 3D relative localization of the objects of interest, making it easier to develop strategies such as collision avoidance. In this work, we developed a framework for detecting drones from depth images using deep learning. The proposed detection technique, while trained only on simulation, has been validated in several real-life depth map sequences. It also generalizes well to multiple types of drones flying at up to 2 m/s, achieving an average precision of 98.7%, an average recall of 74.7% and a record detection range of 9.5 meters.

---

### Real Time Cancer Tumor Tracking for Proton Beam Therapy
![](http://www.saihv.com/images/rtt.png)

In collaboration with Mayo Clinic Arizona, I developed a real-time computer vision based tracking system for markers implanted in tumors. It is common practice to embed tiny fiducial markers in the tumors in order to be visible in the X-ray spectrum. Computer vision techniques such as normalized cross correlation, image saliency maps etc. were utilized in conjunction with kernelized cross-correlation filters to track these tiny markers during X-ray fluoroscopy and estimate their 3D locations. The tracking method is able to handle high amounts of noise and various types of markers in order to achieve accurate and real time tracking.

---

### Ars Robotica: Robots in Theater
![](http://www.saihv.com/images/ar.png)

Ars Robotica was a collaboration between artists and roboticists: to understand the fluidity and expressiveness of human movement. This project tried to define and achieve fluid movement on a Baxter robot. We obtained movement data from expert human performers through various sensors: all the way from a Microsoft Kinect to a 12 camera high-precision, Optitrack system; which we then used as training data to construct "primitives", forming a vocabulary for motion. Later, complex movements were encoded as a temporal combination of such primitives: thus helping create a framework for autonomous interpretation and expression of human-like motion through Baxter.

---

### Micro Subglacial Lake Exploration Device
![](http://www.saihv.com/images/ms.png)

As part of a team at the Extreme Environment Robotics Laboratory, I worked on the development of onboard firmware (Arduino) and ground station software (C#/.NET) for a subglacial lake and aquatic exploration robot called MSLED. MSLED consists of a submersible mothership/explorer combination, and uses MEMS sensor and imaging technologies to investigate deep, remote and chemically challenging aquatic environments. Its sensory payload consists of a camera, inertial measurement unit, CTD sensor, data from which is transferred to the surface through a fiber optic cable. MSLED was deployed successfully twice in Lake McMurdo, Antarctica as part of the WISSARD program, while WISSARD played a crucial role in the discovery of subglacial life under the Antarctic ice.

---

### BENTO Volcano Monitor
![](http://www.saihv.com/images/bb.png)

I led a team of graduate students on a project involving hardware and software design of expendable "volcanic monitor" capsules which monitor and transmit data about rapidly evolving volcanic conditions. The monitors are equipped with a number of sensors (seismic, gas, temperature etc.) and use a minimal data packaging and transmission protocol using the Iridium satellite modems that allows for real time compilation and dissemination of scientific data. Volcano monitors were deployed in Nicaragua, Italy, Iceland and Greenland.

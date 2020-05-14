---
layout: page
title: Projects
---
### Uncertainty-aware Planning for Micro Aerial Vehicle Swarms
![](http://www.saihv.com/images/coplan.png#right)
In this project that forms the second part of my PhD thesis, I investigated the idea of collaborative uncertainty-aware path planning for vision based micro aerial vehicles. For vehicles that are equipped with cameras and can localize collaboratively (see below), a heuristic based approach attempts to capture the estimated "quality" of localization from various viewpoints. Evolutionary algorithms were integrated with an RRT based path planning framework to result in plans which allow the vehicles to navigate intelligently towards areas that can improve their vision based localization accuracy: such as moving only in well-lit locations, observing texture-rich objects, building denser maps before navigating etc.  

---

### Collaborative Localization for Micro Aerial Vehicle Swarms
![](http://www.saihv.com/images/cl.png#right)
As the first part of my PhD thesis, I developed a collaborative localization pipeline that is applicable for a swarm of multirotor aerial vehicles with each vehicle using a monocular camera as its primary sensor. Images are captured continuously from each vehicle and Feature detection and matching are performed between the individual views, thus allowing for reconstruction of the surrounding environment. This sparse reconstruction is then used by the vehicles for individual localization in a decentralized fashion. The vehicles are also capable of computing relative poses between each other and fusing them with individual pose estimation occasionally for enhanced accuracy. Even when cross-correlations between vehicles are not tracked, covariance intersection allows for robust pose estimation between vehicles.

---

### Drone Detection through Depth Images
![](http://www.saihv.com/images/dd.png#right)
In collaboration with researchers from Universidad Politecnica de Madrid and MIT's ACL lab, I am working on a framework for detecting and localizing multirotor UAVs using depth images. A specific advantage of depth sensing versus other detection methods is that a depth map is able to provide 3D relative localization of the objects of interest, making it easier to develop strategies such as collision avoidance. In our work, a dataset of synthetic depth maps of drones has been first generated in the Microsoft AirSim UAV simulator and used to train a state-of-the-art deep learning-based drone detection model. The proposed detection technique, while trained only on simulation, has been validated in several real-life depth map sequences. It also generalizes well to multiple types of drones flying at up to 2 m/s, achieving an average precision of 98.7%, an average recall of 74.7% and a record detection range of 9.5 meters.

---

### Real Time Cancer Tumor Tracking for Proton Beam Therapy
![](http://www.saihv.com/images/rtt.png#right)
In collaboration with Mayo Clinic Arizona, I developed a real-time computer vision based tracking system for markers implanted in cancer tumors. The target application is to control a state-of-the-art proton beam targeting system according to tumor motion which is caused by the breathing cycles of the patient and other kinds of natural organ motion. It is common practice to embed tiny fiducial markers in the tumors in order to be visible in the X-ray spectrum. Computer vision techniques such as normalized cross correlation, image saliency maps etc. are utilized in conjunction with kernelized cross-correlation filters to track these tiny markers during X-ray fluoroscopy. The tracking method is able to handle high amounts of noise and various types of markers in order to achieve accurate and real time tracking.

---

### Ars Robotica: Robots in Theater
![](http://www.saihv.com/images/ars.png#right)
Ars Robotica was a collaboration between artists, theater performers and roboticists: to understand the fluidity and expressiveness of human movement and the possibility of its reproduction by robotic platforms. Using the Rethink Robotics Baxter as a test platform, we worked on defining and achieving human-like movement on the robot. We obtained movement data from expert human performers through various sensors: all the way from a Microsoft Kinect to a 12 camera high-precision, Optitrack system; which we then used as training data to construct "primitives", thus forming a vocabulary for motion. We later managed to express complex movements as a temporal combination of such primitives: thus helping create a framework for autonomous interpretation and expression of human-like motion through Baxter.

---

### Micro Subglacial Lake Exploration Device
![](http://www.saihv.com/images/msled.png#right)
As part of a team at the Extreme Environment Robotics Laboratory, I worked on the development of onboard firmware (Arduino) and ground station software (C#/.NET) for a subglacial lake and aquatic exploration robot called MSLED. MSLED consists of a submersible mothership/explorer combination, and uses MEMS sensor and imaging technologies to investigate deep, remote and chemically challenging aquatic environments. Its sensory payload consists of a camera, inertial measurement unit, CTD sensor, data from which is transferred to the surface through a fiber optic cable. MSLED was deployed successfully twice in Lake McMurdo, Antarctica as part of the WISSARD program, while WISSARD played a crucial role in the discovery of subglacial life under the Antarctic ice.

---

### BENTO Volcano Monitor
![](http://www.saihv.com/images/coplan.png#right)
I led a team of graduate students on a project involving hardware and software design of expendable "volcanic monitor" capsules which monitor and transmit data about rapidly evolving volcanic conditions. The monitors are equipped with a number of sensors (seismic, gas, temperature etc.) and use a minimal data packaging and transmission protocol using the Iridium satellite modems that allows for real time compilation and dissemination of scientific data. Volcano monitors were deployed in Nicaragua, Italy, Iceland and Greenland.

---
layout: post
title:  "Parloma Robotic Hand Builds and Upgrades"
date:   2017-05-30
categories: [news, robotic hand]
---


# Parloma Robotic Hand Builds and Upgrades

In order to make some real-word human interaction trials, two of the Parloma robotic hand and forearm prototypes had been assembled. 
During the process, few parts of the overall system showed up to require some redesign due to poor functionality and/or lack of robustness. Those upgrades are mostly about control communication, power supply distribution and the outer control box. 

## The Hand        
The hands, like much of the forearms, had been reproduced from the original [Parloma model](https://www.thingiverse.com/thing:701446): 24 3D-printed PLA parts put together with glue, self-tapping M2 screws, 8mm alluminum/2mm steel joint axes and 45x3x0.3mm springs. 

![Hand image](/assets/imgs/2018-03-03-parloma-imgs/IMG_0282.png)

Post-processing the printed parts has been critical in order to add tolerances and make them fit together or slide in case of joints.   
Bowden pipes made out of Teflon [(PTFE)](https://en.wikipedia.org/wiki/Polytetrafluoroethylene) had been used to route the artificial tendons through smooth paths within the palm end the forearm toward the motor's pulleys. 

## Forearm 
The outer structure of the forearm, the single-axis robotic wrist as well as the motors/bowden support frame, are kept identical to the original [Parloma Project](https://www.thingiverse.com/thing:701494) 3D models.  

![Forearm image](/assets/imgs/2018-03-03-parloma-imgs/IMG_0354.png)

At this point, we've just started to introduce some necessary improvements. Like the main servo motors that have been upgraded to a newer digital option. Digital servos like the [MG996R](https://www.amazon.com/Qunqi-MG996R-Digital-Torque-Helicopter/dp/B014KONJZY/ref=sr_1_5?ie=UTF8&qid=1520184911&sr=8-5&keywords=MG996R) are capable of higher torque with more  mechanical and thermal stability than their analog counterparts  

Servos power supply distribution and conditioning circuit have been improved as well, leveraging few miniaturized DC-DC step-down [power converters](https://www.amazon.com/eBoot-MP1584EN-Converter-Adjustable-Module/dp/B01MQGMOKI/ref=sr_1_7?ie=UTF8&qid=1520169701&sr=8-7&keywords=Buck+Converter+DC+DC+Step+Down), one for each couple of motors, integrated within the forearm and connected in parallel to the robot's single 12V power input.  

![Power electronics1](/assets/imgs/2018-03-03-parloma-imgs/IMG_0405.png)

The base of the forearm has been redesigned to add functionality and improve robustness combining parametrical and non-parametrical features to fit the organic shape of the forearm's outer mesh geometry. 

The main purpose of the component is to hold all the electrical connections of the robot. Power supply and control data are provided by the external control box through separate cables. 
The connectors, upgraded to more robust options, has been moved to the side of the forearm and are now accessible in more installation scenarios while the extra volume in the component can store more electronics for future upgrades. The connection is also mechanical by means of 3 M4 nuts placed at the bottom surface.   

![Power electronics1](/assets/imgs/2018-03-03-parloma-imgs/IMG_0322.jpeg)

## Control Box 
  
The control box is designed to store in one external module a Raspberry Pi 3, an Arduino Mega and the main power unit, providing all the necessary ports for a smooth set up of the system. There is also a hinged opening to allow easy access to the electronic boards.



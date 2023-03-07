#  Decentralized Formation Control -crazyswarm-

Based on Decentralized Formation Control With Prescribed Distance Constraints and Shape Uniqueness, I design the UAV swarm control experiments which implemented on the crazyswarm2 platform.

## Table of Contents

- [Environment](#environment)
- [Paper](#paper)
- [Abstract](#abstract)
- [Figure](#figure)
- [Video](#video)
- [Contributing](#contributing)

## Environment

system：ROS1 in Ubuntu 20.04（VMware）for simulation & ROS2 in Ubuntu 20.04（VMware）for experiment

Code：python & C++

UAV：Crazyflie 2.1

Platform：crazyswarm https://github.com/USC-ACTLab/crazyswarm & crazyswarm2 https://github.com/IMRCLab/crazyswarm2

Positioning：flow deck & UBW(future)

Firmware：crazyflie-firmware

Communication： crazyradio

## Paper
"Decentralized Formation Control With Prescribed Distance Constraints and Shape Uniqueness"

Yuqi Pan & Binglin He & Yang Wang 

## Abstract
For Multi-Agent Systems (MAS) formation problem, this paper presents a novel decentralized control protocol
that can guarantee the uniqueness of formation shape and
restrain the distance between neighboring agents within a
prescribed range. The proposed control law is decentralized,
in the sense that each agent merely employs local relative
information regarding its neighbors to obtain the control
input. Using a delicately designed gain matrix, we avoid the
problem of non-uniqueness of shape that is existed in the
majority of the decentralized formation methods, especially the
distance-based methods. Meanwhile, the distance constraints,
like connectivity maintenance and collision avoidance, required
in many practical scenarios are also addressed. Furthermore,
the convergence of formation is rigorously proved under a less
restrictive assumption on the communication graph. Finally, a
comparative simulation verifies the effectiveness and superiority
of proposed approach.


## Figure


## Video



## Contributing

See [the contributing file](CONTRIBUTING.md)!

ACC accepted.


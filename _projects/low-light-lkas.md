---
title: "Low-Light Lane Keeping Assistance System"
order: 3
collection: projects
permalink: /projects/low-light-lane
link: "https://github.com/flyingKangaroo1/LowlightLKAS"
link_label: "GitHub"
icon: "fas fa-road"
tags: ["ROS"]
header:
  teaser: "projects/low-light-lkas.png"
---

2024 Winter URP project building a real-time lane keeping system for low-light driving on an Agilex Ranger Mini and NVIDIA Jetson Orin. Camera frames are enhanced on the GPU by a pretrained low-light image enhancement model (Zero-DCE++) and passed to a lane detection model (SRLane), fine-tuned to stop misclassifying sidewalks as lane boundaries. Since the control computer was CPU-only, Zero-DCE++ inference was offloaded to the Jetson Orin over a wired Ethernet ROS network, lifting throughput from 0.3 Hz to 10 Hz, and the system kept the robot centered within its lane through outdoor night tests.

---
title: "Campus 3DGS Map for Simulation"
order: 4
collection: projects
permalink: /projects/campus-gaussian-map
link: "https://youtu.be/i7z6_LPR2l8"
link_label: "Video"
icon: "fas fa-earth-americas"
tags: ["Gaussian Splatting"]
header:
  teaser: "projects/campus-gaussian-map.png"
---

Built as the shared simulation platform for an autonomous driving hackathon hosted for HEVEN club, reconstructing the SKKU campus in 3D so six teams could build and test their own driving algorithms on a scale replica of campus roads. Google Earth imagery is processed through COLMAP for structure-from-motion and 3D Gaussian Splatting for scene reconstruction, then converted to a mesh via GauStudio. The resulting geometry was used to build a road network in RoadRunner and integrated into CARLA as the competition environment.

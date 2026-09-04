---
title: "Sensor Fusion for Autonomous Driving"
order: 1
collection: projects
permalink: /projects/sensor-fusion
link: "https://youtu.be/md7LPKMaJVM"
link_label: "Video"
icon: "fas fa-car"
tags: ["Sensor Fusion", "Autonomous Driving"]
header:
  teaser: "projects/sensor-fusion.mp4"
---

Developed a LiDAR-camera sensor fusion pipeline for cone detection and color classification on an autonomous driving platform for 2025 University Mobility Competition Korea. LiDAR points are clustered via DBSCAN to extract cone centroids, then projected onto YOLO segmentation masks for color classification, improving classification accuracy by 30% over the earlier camera-first approach. Paired with a curvature-adaptive Stanley controller on an ERP42 platform for full closed-loop autonomous driving.

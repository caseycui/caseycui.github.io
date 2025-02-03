---
layout: page
title: 3D Perception
description: Object Detection Using Point Cloud Data and Filter Pipelines
img: assets/img/perception.jpg
importance: 2
category: work
giscus_comments: true
---

Implemented a filtering pipeline (statistical outlier filter, down-sampling, passthrough filter, and RANSAC plane fitting) on Point Cloud data from a
ROS camera node capturing a simulated desktop in Gazebo.

Utilized KD-tree clustering to group filtered points and trained a Support Vector Machine (SVM) using HSV histogram and surface vector features to classify each Point Cloud cluster.

<a href="https://github.com/caseycui/robot_3d_perception">GitHub Repo</a>)

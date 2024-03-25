---
title: "Vision-Based Plane Estimation and Following for Building Inspection With Autonomous UAV"
collection: publications
permalink: /publication/inspection 
excerpt: 'In this article, we focus on enabling the autonomous perception and control of a small unmanned aerial vehicle (UAV) for a façade inspection task. Specifically, we consider the perception as a planar object pose estimation problem by simplifying the building structure as a concatenation of planes, and the control as an optimal reference tracking control problem.'
date: 2023-10-13
venue: 'IEEE Transactions on Systems, Man, and Cybernetics: Systems (TSMC-S)' 
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10218325'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
teaser: 'images/dmll-slam.gif'
authors: 'Wu Y., Zhao C., **Lyu Yang**'
break: 'yes'
---
This article presents differential-map-aided LiDAR-based localization (DMLL), a localization framework that combines map-based localization and LiDAR odometry to achieve accurate and reliable robot pose estimation in partially known environments. In DMLL, measurement from map-matching are novelly modeled as differential constraints in the factor graph, rather than absolute constraints. This simplifies the fusion process and avoids initial alignment errors. We design uncertainty quantization for both the LiDAR odometry measurement and the map-matching measurement. Furthermore, we design an adaptive decision mechanism that selectively triggers the map-matching module based on the quantified uncertainty of these measurements. This mechanism achieves a balance between resource consumption and localization accuracy while also being capable of detecting and discarding erroneous data, thus improving the overall localization reliability. Our proposed method is extensively evaluated on both public datasets and our own field-collected data. The result indicates that our method can achieve highly accurate localization in practical scenarios.
\[[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10439642)\]\[[Video](https://youtu.be/HsY04_7ulgg)\]

<img style="float: center;" src="/images/dll-slam.gif">

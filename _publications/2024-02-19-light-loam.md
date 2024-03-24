---
title: "Light-LOAM: A Lightweight LiDAR Odometry and Mapping based on Graph-Matching"
collection: publications
permalink: /publication/Light-LOAM
excerpt: 'This paper propose a light-weight LOAM system by implementing the Graph-Matching based point clouds association. \[[Video](https://youtu.be/cdWClOPjL-4)\]\[[Code](https://github.com/BrenYi/Light-LOAM)\]'
authors: 'Yi S., **Lyu Yang**, Hua L., Pan Q., and ZHao C.'
date: 2024-02-19
venue: 'IEEE Robotics and Automation Letters (RAL)'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10439642'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
teaser: 'images/light-loam.gif'
break: 'yes'
breakagain: 'yes'
---
Simultaneous Localization and Mapping (SLAM) plays an important role in robot autonomy. Reliability and efficiency are the two most valued features for applying SLAM in robot applications. In this letter, we consider achieving a reliable LiDARbased SLAM function in computation-limited platforms, such as quadrotor UAVs based on graph-based point cloud association. First, contrary to most works selecting salient features for point cloud registration, we propose a non-conspicuous feature selection strategy for reliability and robustness purposes. Then a two-stage correspondence selection method is used to register the point cloud, which includes a KD-tree-based coarse matching followed by a graph-based matching method that uses geometric consistency to vote out incorrect correspondences. Additionally, we propose an odometry approach where the weight optimizations are guided by vote results from the aforementioned geometric consistency graph. In this way, the optimization of LiDAR odometry rapidly converges and evaluates a fairly accurate transformation resulting in the back-end module efficiently finishing the mapping task. Finally, we evaluate our proposed framework on different datasets and real-world environments. Experiments show that our SLAM system achieves a comparative level or higher level of accuracy with more balanced computation efficiency compared with the mainstream LiDAR-based SLAM solutions.
\[[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10439642)\][[Video](https://youtu.be/cdWClOPjL-4)\]\[[Code](https://github.com/BrenYi/Light-LOAM)\]'

<img style="float: center;" src="/images/light-loam.gif">

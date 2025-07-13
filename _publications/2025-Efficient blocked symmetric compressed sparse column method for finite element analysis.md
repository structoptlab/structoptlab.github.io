---
title: "Efficient blocked symmetric compressed sparse column method for finite element analysis"
collection: publications
category: manuscripts
permalink: /publication/2025-Efficient blocked symmetric compressed sparse column method for finite element analysis
excerpt: 'Yingjun Wang, Shijie Luo, Jinyu Gu, Yuanfang Zhang'
date: 2025-02-01
venue: 'Frontiers of Mechanical Engineering'
paperurl: 'http://structoptlab.github.io/files/2025-Efficient blocked symmetric compressed sparse column method for finite element analysis.pdf'
---
In finite element analysis (FEA), optimizing the storage requirements of the global stiffness matrix and enhancing the computational efficiency of solving finite element equations are pivotal objectives. To address these goals, we present a novel method for compressing the storage of the global stiffness matrix, aimed at minimizing memory consumption and enhancing FEA efficiency. This method leverages the block symmetry of the global stiffness matrix, hence named the blocked symmetric compressed sparse column (BSCSC) method. We also detail the implementation scheme of the BSCSC method and the corresponding finite element equation solution method. This approach optimizes only the global stiffness matrix index, thereby reducing memory requirements without compromising FEA computational accuracy. We then demonstrate the efficiency and memory savings of the BSCSC method in FEA using 2D and 3D cantilever beams as examples. In addition, we employ the BSCSC method to an engine connecting rod model to showcase its superiority in solving complex engineering models. Furthermore, we extend the BSCSC method to isogeometric analysis and validate its scalability through two examples, achieving up to 66.13% memory reduction and up to 72.06% decrease in total computation time compared to the traditional compressed sparse column method.

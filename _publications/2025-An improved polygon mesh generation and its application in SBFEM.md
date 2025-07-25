---
title: "An improved polygon mesh generation and its application in SBFEM using NURBS boundary"
collection: publications
category: manuscripts
permalink: /publication/2025-An improved polygon mesh generation and its application in SBFEM
excerpt: 'Xinqing Li, Hailiang Su, Yingjun Wang'
date: 2025-01-01
venue: 'Computational Mechanics'
paperurl: 'http://structoptlab.github.io/files/2025-An improved polygon mesh generation and its application in SBFEM.pdf'
---
Aiming to address the challenge of inaccurately describing the curve boundary of the complex design domain in traditional finite element mesh, this paper proposes an improved polygon mesh generation and polygon scaled boundary finite element method (PSBFEM) using non-uniform rational B-spline (NURBS) boundary. In the improved mesh generation scheme, the domain boundary will be accurately described using NURBS curves. Within this framework, a NURBS updating strategy is proposed, allowing the NURBS curve information on the boundary to be updated as the mesh changes. By employing point inversion and knot insertion, additional control points are introduced to ensure that some coincide with the nodes of the elements, thereby guaranteeing the accuracy of subsequent analyses. The boundary elements can be discretized into NURBS elements and conventional elements using SBFEM, whose physical fields are respectively constructed using NURBS basis functions and Lagrange shape functions in the circumferential direction. In the radial direction, by transforming a system of partial differential equations into a system of ordinary differential equations, which can be analytically solved without fundamental solutions. Furthermore, the internal elements can be solved directly with the traditional polygon SBFEM. The numerical examples demonstrate that the proposed method can achieve a high-quality polygon mesh with NURBS updating. Moreover, it effectively solves the corresponding polygon elements and significantly improves the accuracy of the displacement and stress solutions compared to the traditional polygon SBFEM.

---
layout: project
title: MAE 4700 Airplane Wing
description: 
technologies: [Ansys Discovery, Ansys Mechanical]
image: /assets/images/transparent_wing.png
permalink: /wing/
---

In the class MAE 4700: Finite Element Analysis for Mechanical and Aerospace Design, we learned the improtance of the Finite Element Method in approximating partial differential equations. In most mechanical and aerospace applications, complex designs mut be verified and optimized using simulations that employ the Finite Element Method. Using that standard, this project focuses on optimizing a simplified airplane wing model using FEM through the powerful tools the Ansys Workbench provides, with the ultimate goal of finding the lightest, yet structurally sound geometry. 

The approach to solve this problem was to parametrize various design variables (e.g., skin thickness, number of ribs, placement of the spar(s)) while optimizing the weight and meeting our constraints ($$FOS > 1.5$$ and $$\delta_{max} < 0.375m$$). This study found a wing with two spars and six ribs placed at various locations yielded the best results, achieving a $$FOS > 2.1559$$ and a $$\delta_{max} = 0.37455 m$$, while minimizing the geometric mass by 41.6% compared to the baseline design. 

Take a look at the full report [here]({{ "/assets/4700_5700_Final_Project.pdf" | relative_url }}).

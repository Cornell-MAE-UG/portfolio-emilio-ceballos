---
layout: project
title: MEng. Capstone Project
description: Holistic project incorporating 
technologies: [Autodesk Fusion, MATLAB]
image: /assets/images/uc24render.png
---

In MAE 4272, our team designed, fabricated, and tested a small-scale horizontal-axis wind turbine blade optimized for power generation under a realistic wind environment. The blade was designed around a Weibull-distributed wind profile representative of lab conditions, with the objective of maximizing power extraction while remaining within strict geometric, material, and rotational constraints. The final design used a NACA 4412 airfoil, was limited to a 6-inch span, compatible with a standard hub, and constrained to operate below 2000 RPM without structural failure

![Shaded rendering of earlier version]({{ "/assets/images/wind_blades_printed.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

Our design approach combined blade element theory with an iterative MATLAB-based optimization framework. Using the cubic form of the Weibull distribution, we identified an optimal design wind speed of 4.17 m/s, then selected blade geometry to maintain a near-constant angle of attack along the span. Chord, pitch, and twist distributions were generated across the blade length while enforcing stress limits based on the flexural strength of the Accura 25 material. Structural checks showed the blade experienced stresses well below failure limits at the final operating point of 1100 RPM, ensuring a large factor of safety while preserving aerodynamic performance

![Photo of old radio]({{ "/assets/images/wind_blade_power_curves.png" | relative_url }}){: .inline-image-l}

The fabricated blades were experimentally tested in a wind tunnel using a magnetic particle brake to generate power curves across multiple wind speeds. Data acquisition included wind speed, torque, rotational speed, and mechanical power, allowing us to generate power curves and estimate aerodynamic efficiency. While the blades demonstrated structural integrity across all test conditions, testing revealed unexpected low-RPM behavior below ~1500 RPM, preventing sustained operation at the design point. Despite this limitation, higher wind-speed tests showed increasing efficiency trends and validated the blade’s ability to withstand aerodynamic loading without damage

I led the development of the experimental testing protocol and coordinated wind tunnel testing, including data acquisition setup, calibration, and collection. I also contributed to validating structural safety prior to testing and supported data interpretation during post-processing, particularly when low-RPM behavior was observed.

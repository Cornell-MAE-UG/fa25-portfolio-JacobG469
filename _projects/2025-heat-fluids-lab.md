---
layout: project
title: MAE 4272 - Fluids/Heat Transfer Design Project
description: Blade Design Group Project
technologies: [Autodesk Fusion]
image: /assets/images/blade-image.png
---

For this project, my group was tasked with designing and optimizing a small-scaled wind turbine blade for provided low-wind conditions. We designed a system that allowed us to iterate through different designs using an optimizer that would output model predictions that met our requirements and worked with out design assumptions. The blade itself was was designed under the assumptions that we were operating with steady 2D flow, negligible friction and 3D effects, and a Reynold's Number of 50,000 with provided data. Additionally, we were tasked with designing a blade that could withstand a given stress level and work with a factor of safety of at least 1.5. Our optimizer took our requirements and the NACA 4412 airfoil we chose to match good performance at low Re, and ran through differential evolution that generated designs that would meet our needs. The best output was then used to drive the CAD model we needed to printing the blades for testing.

Our testing involved running our blade turbine design through our small-scale laboratory wind tunnel at the predicted optimal windspeed, then using a fixed torque-brake to measure the output power of the wind turbine at various RPMs, giving us appropriate power curves necessary to understanding the effectiveness of our design to efficiently extract power. Beyond the predicted optimal windspeed, we decided to perform sweeps of power outputs at different RPMs for increasing windspeed steps. This worked to give us a better perspective of how the blades performed. Ultimately, our design did not generate data at the optimal windspeed given a flaw in the design but we proceed to collect data at higher windspeeds that gave us enough data to analyze the performance of the blades at windspeeds that would allow it to rotate. We were able to collect power data that was unfortunately a small fraction of what we anticipated (magnitude-wise), but our design held up under load and functioned at around the optimal RPM range we found (more can be seen in plots below). My contributions to this project came in the form of detailing our testing and analysis procedures, ensuring that we were able to collect enough data to give us a meaningful view of our design and then determine the performance of our design.

---
Plots and Tables: 

![Power vs RPM](/fa25-portfolio-JacobG469/assets/images/rpm.jpg)
Power vs RPM

![Blade Data](/fa25-portfolio-JacobG469/assets/images/table.jpg)
Blade Data

---




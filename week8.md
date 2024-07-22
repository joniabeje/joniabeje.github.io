---
layout: post
title: Week 8
author: Jonathan Abeje
---

### Accomplishments
This week, we dedicated our efforts to debugging and refining our detection code, as well as implementing a function to monitor speeding vehicles. Our primary focus was on ensuring the stability and accuracy of the system, resolving issues that caused premature termination, and adding functionality to identify and log speeding vehicles.

### Results
By the end of the week, our code was running smoothly without unexpected terminations, and the new speeding detection function was operational. The system now effectively identifies vehicles exceeding the speed limit and logs this information for further analysis. This improvement enhances the capability of our traffic monitoring system to not only detect red-light dashers and jaywalkers but also track speeding violations.

### Findings
Throughout the debugging process, we learned the importance of robust error handling and thorough testing. Identifying and fixing the root causes of abrupt terminations required a meticulous approach. Additionally, integrating the speeding detection feature provided valuable insights into the complexities of real-time speed calculation and the need for precise calibration to ensure accuracy.

### Algorithm(s) used
We continued utilizing the YOLOv8 object detection model, enhancing it with a new module for speed calculation. This module leverages the pixel-per-meter ratio to estimate vehicle speed accurately. The system now logs detections, traffic light status, jaywalking incidents, and speeding violations, creating a comprehensive dataset for traffic analysis.

### Issues/Frustrations Encountered
One of the significant challenges was pinpointing the exact causes of the immediate termination issue. This required extensive debugging and testing. Additionally, integrating the speeding function demanded careful calibration and validation to ensure the speed calculations were accurate and reliable. Balancing real-time performance with accurate detection and logging was a consistent challenge.

[Back](/.)

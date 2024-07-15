---
layout: post
title: Week 5
author: Jonathan Abeje
---

### Accomplishments
This week, we focused on enhancing our integration of YOLOv8 object detection with custom HSV-based color detection and region of interests (ROIs). We successfully implemented multiple ROIs for detecting traffic lights and crosswalks, which allowed us to identify jaywalking incidents when the traffic light was green. This integration ensured that the detection of persons within the crosswalk during a green light was accurate and labeled as jaywalkers. We also refined the mask and contour detection to improve the precision of traffic light color identification.

### Results
By the end of the week, our combined detection script accurately identified and labeled red, yellow, and green traffic lights within the specified ROIs. It also detected persons, cars, and trucks using YOLOv8, and correctly labeled jaywalkers in real-time. The system maintained effective real-time processing capabilities, ensuring smooth and precise detection.

### Findings
We learned that precise ROI selection is crucial for accurate jaywalking detection. Combining YOLOv8 for object detection with HSV color space processing for traffic light color identification proved to be an effective approach. The use of morphological operations and contour detection significantly enhanced the ability to isolate traffic lights from complex backgrounds, improving overall detection accuracy.

### Algorithm(s) used
We utilized a combination of YOLOv8 object detection and HSV color space-based detection algorithms. YOLOv8 was used for detecting persons, cars, and trucks, while HSV processing, combined with contour detection and morphological operations, was used for detecting and labeling red, yellow, and green traffic lights within selected ROIs.

### Issues/Frustrations Encountered
The main challenge I encountered was integrating YOLOv8 with custom HSV ranges and ROIs. This brought difficulties related to the processing speed and managing concurrent detections to ensuring smooth real-time processing. Through iterative adjustments and thorough testing, we overcame these obstacles, achieving precise detection results and a robust detection system. I also plan on using the NVIDIA GPU instead of my computer's CPU in order to process the frames per second faster.

[Back](./)

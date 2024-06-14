---
layout: post
title: Week 3
author: Jonathan Abeje
---

Accomplishments

This week, we focused on enhancing the detection of traffic lights using HSV color space. We began by implementing basic HSV color detection for yellow, followed by refining our approach to differentiate the yellow light from backgrounds using contour detection and morphological operations. We then expanded our detection capabilities to include red and green lights, defining their specific HSV ranges and handling the dual HSV ranges required for red detection. We adapted our code to process video files frame by frame, ensuring real-time detection and labeling of traffic lights. Additionally, we added error handling to improve robustness in video file loading and frame capture.

Results

By the end of the week, our detection script successfully identified and labeled red, yellow, and green traffic lights in video frames. The script demonstrated high accuracy in differentiating the lights from their backgrounds and provided real-time processing capabilities. This was a significant step forward in our traffic video analysis project.

Findings

Through our work, we gained a deeper understanding of the HSV color space and the importance of fine-tuning color ranges for accurate detection. We discovered that managing dual HSV ranges for red and adjusting the HSV range for green was crucial for improving detection accuracy. The use of contour detection and morphological operations significantly enhanced our ability to isolate the lights from the background.

Algorithm(s) Used

We utilized HSV color space-based detection algorithms combined with contour detection and morphological operations. These methods were implemented to refine the masks and improve the accuracy of detecting red, yellow, and green traffic lights in video frames.

Issues/Frustrations Encountered

This week, we encountered challenges in accurately differentiating yellow lights from yellow backgrounds and fine-tuning the HSV range for green detection. However, through iterative adjustments and testing, we were able to overcome these challenges and achieve accurate detection results.

[Back](./)

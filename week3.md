---
layout: post
title: Week 3
author: Jonathan Abeje
---

Accomplishments

During this week, we concentrated on advancing the detection of traffic lights using the HSV color space. We initiated our efforts with the basic detection of yellow lights and improved our approach by integrating contour detection and morphological operations to better distinguish the yellow light from its background. Subsequently, we expanded our detection capabilities to encompass red and green lights, defining their specific HSV ranges and handling the dual HSV ranges required for red. Additionally, we modified our code to process video files frame by frame, allowing for real-time detection and labeling of traffic lights. We also incorporated error handling to enhance the robustness of video file loading and frame capture.

Results

By the end of the week, our detection script was successfully identifying and labeling red, yellow, and green traffic lights in video frames. The script demonstrated high accuracy in distinguishing the lights from their backgrounds and enabled real-time processing. This marked a significant advancement in our traffic video analysis project.

Findings

Throughout the week, we gained a deeper insight into the HSV color space and the critical role of fine-tuning color ranges for accurate detection. We discovered that managing dual HSV ranges for red and adjusting the HSV range for green were crucial for improving detection precision. The use of contour detection and morphological operations greatly enhanced our ability to isolate the lights from the background.

Algorithm(s) Used

We utilized detection algorithms based on the HSV color space, combined with contour detection and morphological operations. These techniques were implemented to refine the masks and enhance the accuracy of detecting red, yellow, and green traffic lights in video frames.

Issues/Frustrations Encountered

This week, we encountered challenges in accurately differentiating yellow lights from yellow backgrounds and fine-tuning the HSV range for green detection. However, through iterative adjustments and thorough testing, we managed to overcome these obstacles and achieve precise detection results.

[Back](./)

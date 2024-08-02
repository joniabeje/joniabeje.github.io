---
layout: post
title: Week 10
author: Jonathan Abeje
---

### Final Journal Entry

**Week Overview:**

My final week at the CEAMLS Summer AI Research Institute was a culmination of months of intensive research and development in building a traffic monitoring system using computer vision and AI techniques. On Monday, I finalized the technical aspects of the project, ensuring that all components were functioning as intended. This set the stage for my final presentation on Tuesday, where I showcased the system's capabilities and the insights we gleaned from our testing. Wednesday marked the official conclusion of my project work, allowing me to reflect on the outcomes and challenges faced throughout the program. The remainder of the week, Thursday and Friday, was dedicated to writing and refining our research paper, capturing the essence of our findings and the potential impact of our system.

**Project Summary:**

Our project aimed to enhance traffic safety through an AI-powered system capable of detecting traffic violations such as jaywalking and red-light running. We utilized the YOLOv8n model, known for its high accuracy and processing speed, alongside the OpenCV library for computer vision tasks and HSV color detection for identifying traffic light states. The integration of SQL databases allowed us to efficiently store and query detected data, improving the system's reliability and accuracy.

**Key Achievements:**

1. **Successful Detection and Validation:**
   - The system effectively detected jaywalkers and red-light dashers, achieving notable accuracy metrics. For instance, jaywalking detection attained a precision of 1, signifying complete accuracy when detected. SQL validation played a crucial role in refining our detections by filtering out false positives and ensuring that only legitimate violations were recorded. This validation step was pivotal in reducing the predicted jaywalker count from 14 to 6, aligning perfectly with the ground truth.

2. **Comprehensive Evaluation Metrics:**
   - We employed a range of evaluation metrics, including accuracy, precision, recall, F1 score, and F2 score, to assess the system's performance. The accuracy for jaywalking was 81.94%, while red-light dashing reached 94.45%. These metrics highlighted the system's capability in detecting violations accurately within a controlled 30-minute video segment.

3. **SQL Integration for Enhanced Accuracy:**
   - Implementing SQL validation allowed us to effectively reduce false positives by enforcing criteria such as minimum detection durations (e.g., objects must be detected for at least 2 seconds to be classified). This integration proved crucial in aligning our predictions with actual results, showcasing the value of database-driven validation in AI applications.

**Challenges and Learnings:**

While the system performed well under controlled conditions, we identified several areas that warrant further exploration and improvement:

1. **Dependence on Dataset and Environmental Conditions:**
   - The accuracy observed is closely tied to the controlled conditions of the 30-minute video footage. In real-world scenarios, extended footage spanning 24 hours or more would introduce varying lighting conditions, weather changes, and dynamic traffic patterns, likely impacting accuracy. Longer footage would require rigorous testing to understand how these factors affect the system's performance.

2. **False Positives and False Negatives:**
   - Despite high precision in certain metrics, the system still faced challenges with false negatives, particularly in jaywalking detection. Some instances were missed due to brief occlusions or rapid movements, highlighting the need for continuous improvements in object tracking and classification.

3. **Future Testing and Real-World Application:**
   - Before deploying the system in real-time traffic environments, extensive testing across diverse settings is essential. This would help ensure the model's robustness and reliability in detecting traffic violations under varied conditions.

**Conclusion and Future Directions:**

The CEAMLS program has been an invaluable experience, providing an opportunity to apply AI and computer vision techniques to real-world problems. Our traffic monitoring system demonstrates the potential of technology in enhancing traffic safety and informing policy decisions. Future iterations of this project will focus on increasing robustness and accuracy, particularly by incorporating more advanced YOLO models and exploring GPU integration for faster processing speeds.

By continuing to refine and test our system, we aim to contribute to safer urban environments, enabling data-driven decisions for traffic management and safety improvements. This project represents a significant step toward realizing the potential of AI in transforming traffic safety and underscores the importance of continued research and innovation in this field. 

[Back](/.)

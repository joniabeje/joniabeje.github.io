---
layout: post
title: Week 8
author: Jonathan Abeje
---

### Accomplishments
This week, we focused on refining the detection logic, specifically addressing the identification of red-light dashers. We implemented a condition to ensure that only vehicles flagged as dashers by the YOLO model are logged as red-light dashers. Additionally, we improved our SQL queries to accurately reflect these detections in our database, avoiding false positives.

### Results
By the end of the week, our system correctly identified and logged only those vehicles marked as red-light dashers by the YOLO model. The database now accurately reflects these events, reducing the number of false positives from 23 to the correct count of 3. This refinement significantly enhances the reliability of our traffic violation detection.

### Findings
During the refinement process, we learned the critical importance of precise conditional checks within our detection logic. Ensuring that only specific vehicle types (cars, trucks, and buses) could be marked as red-light dashers was essential to improve accuracy. This process also highlighted the need for continuous testing and validation to ensure the detection logic aligns with real-world scenarios.

### Algorithm(s) used
We continued utilizing the YOLOv8 object detection model, focusing on enhancing its capability to accurately detect and log red-light dashers. The updated logic now includes a condition to check for specific vehicle types and only mark them as dashers when the YOLO model prints 'Dasher' on the screen. This enhancement ensures that our logging mechanism is accurate and reliable.

### Issues/Frustrations Encountered
A significant challenge this week was ensuring that only the correct vehicles were marked as red-light dashers. This required revisiting the detection logic and adding specific conditions to filter out false positives. Additionally, updating the SQL queries to reflect these changes accurately in the database required careful consideration and testing. Balancing the detection accuracy with real-time processing continued to be a challenging aspect of the project.

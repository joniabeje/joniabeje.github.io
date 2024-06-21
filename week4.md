



### Accomplishments

During this session, we focused on advancing the integration of YOLOv8 object detection with custom HSV-based color detection for traffic lights. We started by ensuring the selection of Regions of Interest (ROIs) in video frames, which allows users to focus detection on specific areas, such as traffic lights. We then successfully combined YOLOv8 for detecting specific objects (person, car, truck) and custom HSV processing for identifying traffic light colors. This integration included handling dual HSV ranges for red, improving mask refinement using morphological operations, and ensuring real-time frame-by-frame processing.

### Results

By the end of the session, our combined detection script accurately identified and labeled red, yellow, and green traffic lights within the specified ROIs while concurrently detecting persons, cars, and trucks using YOLOv8. The refined mask and contour detection significantly improved the precision of traffic light detection, and the system demonstrated effective real-time processing capabilities.

### Findings

Throughout the session, we gained a deeper understanding of the importance of combining YOLOv8's object detection with HSV color space processing for focused tasks. Managing dual HSV ranges for red and adjusting HSV ranges for yellow and green were critical for accurate traffic light detection. The use of morphological operations and contour detection greatly enhanced the ability to isolate traffic lights from complex backgrounds.

### Algorithm(s) Used

We utilized a combination of YOLOv8 object detection and HSV color space-based detection algorithms. YOLOv8 was used for detecting persons, cars, and trucks, while HSV processing, combined with contour detection and morphological operations, was used for detecting and labeling red, yellow, and green traffic lights within selected ROIs.

### Issues/Frustrations Encountered

We encountered challenges in accurately differentiating yellow lights from yellow backgrounds and fine-tuning the HSV range for green detection. Additionally, integrating YOLOv8 with custom HSV processing posed complexities in managing concurrent detections and ensuring smooth real-time processing. Through iterative adjustments and thorough testing, we overcame these obstacles, achieving precise detection results and a robust detection system.

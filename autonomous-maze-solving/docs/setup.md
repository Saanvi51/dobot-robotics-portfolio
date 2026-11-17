# Hardware and technical notes — Autonomous maze solving

These notes describe the original experiment. **The source implementation is not included in this public portfolio.**

- **Robot and materials:** Dobot Magician Lite with pen/tool, camera, and a printed maze.
- **Software stack:** Python, OpenCV, NumPy, graph search (BFS), calibrated homography, and Gemini vision for endpoint classification in challenging lighting.
- **Method:** detect maze corners, correct perspective, construct grid occupancy, locate endpoints, plan a path, and map the path back into robot coordinates for tracing.
- **Experimental artifacts:** example calibration and path-output JSON files are retained as data from the original experiment, not as instructions or a reproducible software package.
- **Engineering considerations:** calibration is specific to the camera and physical workspace; early corner-detection experiments using YOLO were less consistent than the later contour-based approach.

See the [lab report](lab_report.pdf) and [demonstration](https://youtu.be/d2KFqwhLtJA).

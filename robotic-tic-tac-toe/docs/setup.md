# Hardware and technical notes — Robotic tic-tac-toe

These notes describe the original experiment. **The source implementation is not included in this public portfolio.**

- **Robot and materials:** Dobot Magician Lite with pen, camera, drawing surface, and a 60 mm × 60 mm tic-tac-toe board.
- **Software stack:** Python, OpenCV, a minimax game-playing algorithm, and a compatible Dobot controller.
- **Method:** draw the grid, detect human marks through camera/ROI processing, update game state, choose a move using minimax, and draw the robot response.
- **Engineering considerations:** the camera view, pen height, grid coordinates, and symbol detection were sensitive to calibration, perspective, and lighting.
- **Limitations:** physical trials exposed symbol-localization problems despite successful game logic, as described in the report.

See the [lab report](lab_report.pdf) and [demonstration](https://youtu.be/Gvnxh9V4Tv8).

# Hardware and technical notes — Natural-language pick-and-place

These notes describe the setup used for the original RAS 545 experiment. **The source implementation is not included in this public portfolio.**

- **Robot and materials:** Dobot Magician Lite with suction end effector, colored plastic blocks, camera, and calibrated work surface.
- **Software stack:** Python, OpenCV, Google Gen AI SDK (Gemini), and a compatible Dobot control API.
- **Method:** detect colored block positions, estimate robot coordinates through a pixel-to-robot homography, interpret spoken or typed natural-language requests into structured action steps, and execute supported manipulations.
- **Engineering considerations:** camera resolution affected calibration; multiple blocks of the same color required object selection; relative placement commands required coordinate-direction validation.
- **Hardware dependence:** camera mounting, robot workspace, and robot control libraries differ between environments. The archived homography JSON is experimental data, not general-purpose motion parameters.

See the [lab report](lab_report.pdf) for details and the [demonstration](https://youtu.be/ppjOnzXohbc) for the completed project.

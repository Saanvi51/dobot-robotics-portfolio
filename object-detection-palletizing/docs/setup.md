# Hardware and technical notes — Object detection and palletizing

These notes describe the original experiment. **The source implementation is not included in this public portfolio.**

- **Robot and materials:** Dobot Magician Lite with suction end effector, USB camera, two labeled drop pallets, and printed food/vehicle object cards.
- **Software stack:** Python, YOLO/Ultralytics, computer vision, and a compatible Dobot control interface.
- **Method:** capture the scene from a fixed detection pose, classify objects, select the appropriate category pallet, and move the object.
- **Experimental context:** the project used robot poses and camera settings calibrated for the original Ubuntu lab setup.
- **Limitations:** detection was scoped to supported food and vehicle labels; the report documents class-lab observations rather than a formal detection-accuracy benchmark.

See the [lab report](lab_report.pdf) and [demonstration](https://youtu.be/YzFnglL5R7w).

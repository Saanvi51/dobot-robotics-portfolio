# Hardware and technical notes — Suction vs. mechanical gripper

These notes describe the physical setup from the original RAS 545 experiment. **The source implementation is not included in this public portfolio.**

## Experimental system

- **Robot:** Dobot Magician Lite
- **End effectors:** vacuum suction cup and mechanical gripper
- **Workspace:** two secured pallets and four test blocks
- **Control environment:** Python with the robot-control API used for the class lab, reported as `pydobot2` on Ubuntu 22.04
- **Calibration:** taught source, destination, approach, and retreat poses specific to the original workspace

## Engineering considerations

The baseline suction routine used intermediate travel poses; the optimized routine reduced redundant travel. The mechanical gripper required different clearance heights because its jaws were larger than the suction tool. These adjustments are specific to the original test setup.

The experimental timings are recorded in the [lab report](lab_report.pdf) and summarized in the [project README](../README.md). The report does not establish repeatability across different hardware or objects.

See the [demonstration](https://youtu.be/mT_Njtg9VYs).

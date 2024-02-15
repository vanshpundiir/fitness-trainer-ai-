## Pose Trainer: Correcting Exercise Pose using Pose Estimation



Please follow the instructions at 
https://github.com/CMU-Perceptual-Computing-Lab/openpose/blob/master/doc/installation/0_index.md#windows-portable-demo
to download and set up OpenPose, and move it into the root folder of the repository.
(ex. If this repository is x/y/z/pose-trainer, then OpenPose should be placed at x/y/z/pose-trainer/openpose.)

Pose trainer has been tested with OpenPose 1.7.0.

- Pose Trainer is designed to run on Windows only, since it uses the Windows portable version of OpenPose.
- Pose Trainer expects the OpenPose folder to be in Pose Trainer's repository folder.
- Pose Trainer should be run from the root folder of the repository using main.py.
- Pose Trainer requires Python with the necessary libraries installed.

`main.py` is the primary script for running Pose Trainer. For options: `py main.py --help`

Sample command: `py main.py --mode evaluate --video sample_bicep_curl.mp4`

About speed:

- OpenPose can run on a CPU-only machine, but it will be very slow.
- If you have a computer with an NVIDIA GPU, OpenPose will run significantly faster.

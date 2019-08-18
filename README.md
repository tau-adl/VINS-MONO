# VINS-MONO
VINS-MONO theoretical overview and implementation analysis - Daniel Roth M.Sc project

This project  is an experiment on state estimation algorithm based on visual and inertial data using a miniature drone (CrazyFlie).

The purpose of the project is achieve a reliable drone state estimation using only the onboard IMU and an add-on camera. The algorithm used is VINS-MONO, and the selected drone is Crazyflie that was mounted with a small low-cost RGB camera.

Drone pose estimation is a task that was solved in numerous ways – the contribution of this project is the use of the VINS-MONO algorithm along with the low cost setup of the Crazyflie and the camera. To our knowledge this was not done before.
This project will elaborate on the theoretical and software stages of the algorithm, the software environments used, the hardware that was used and failures and solutions that we encountered through the project.
Additionaly, we present the benefits of the setup and our experiments.


# Extended-Kalman-Filter
 
The purpose is applying the Extended Kalman Filter to estimate the trajectory of a robot based on input signals and range/bearing measurements from a LIDAR sensor. It combines the motion model of the robot with measurement updates to iteratively refine the state estimate and covariance, providing an estimation of the robot's position and orientation over time.


![grand truth trajectory](https://github.com/easensoy/Extended-Kalman-Filter---AV/assets/76905667/327b46ce-b379-4ecc-9296-4c6ad7cd63a8)

![grand truth trajectory_2](https://github.com/easensoy/Extended-Kalman-Filter---AV/assets/76905667/68e7f977-6600-47af-8786-34dab6ff1608)

The Jacobian matrix is used in the Extended Kalman Filter (EKF) implementation to linearize the system dynamics and update the state estimate during the prediction and update steps. In the context of quaternions, the Jacobian matrix is needed to propagate the covariance matrix and update the state estimate based on the measured sensor data.
![jacobians](https://github.com/easensoy/Extended-Kalman-Filter---AV/assets/76905667/a92530e9-acf7-4004-a6c1-ac2cf78f49ed)

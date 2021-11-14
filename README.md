# Modell-identification-and-trajectory-planning
A Robust Data Driven Approach for Dynamics Model Identification in Trajectory Planning

Chen, Jiangqiu and Zhang, Mingyu and Yang, Zhifei and Xia, Linqing


YouTube: https://www.youtube.com/watch?v=rZSfZJxPOkc&t=135s

Abstract—In this paper, we propose a data-driven modelling framework using a sparse regression technique to find the governing equations of dynamics systems. With this approach, the prior knowledge of features from simple structures can be used to deduce which on complex structures. The prior knowledge of single-pendulums, double-pendulums, and spherical pendulum enlightens the guess of the feature library for a 3-DOF manipulator. The feature library is sparsified with a fully autonomous machine learning algorithm composited of the L1-regularization and proportional filter. The training dataset with non-zero-mean Gaussian noise simulates real- world conditions and proves the system's robustness to the noise. Compared with the neural-network-based system identification method, this paper's technique can be promptly applied in dynamic trajectory planning. A simulation of the optimal trajectory planning for the obstacle-avoidance on the Lynxmotion robot is accomplished by optimizing the objective function constructed with energy and penalty function. Results of the simulation support that the estimated model works correctly. Comparison between the data-driven and the closed- form model evidences the reliability and robustness of this identification technique.

## Block diagram:
<p align="center">
<img src="model identification and trajectory planning/result_svg/Blank diagram.svg">
</p>

## Results:

### Denoise:
<p align="center">
<img src="model identification and trajectory planning/result_svg/denoise.svg">
</p>

### Model Fitting:
<p align="center">
<img src="model identification and trajectory planning/result_svg/t1t.svg" width="450"/>
<img src="model identification and trajectory planning/result_svg/t2t.svg" width="450"/>
<img src="model identification and trajectory planning/result_svg/t3t.svg" width="450"/>
</p>

### Energy optimization:
<p align="center">
<img src="model identification and trajectory planning/result_svg/0330Energy.svg" width="600">
</p>

### Dynamic Trajectory Planning:
<p align="center">
<img src="model identification and trajectory planning/result_svg/0303DTG.svg">
<img src="model identification and trajectory planning/result_svg/distanceToObstacle.svg">
</p>

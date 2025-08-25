# Exploring-Narrow-and-Unknown-Environments-with-Tactile-Sensing-Robots
Exploring Narrow and Unknown Environments with Tactile Sensing Robots
In narrow and unknown environments, traditional path planning methods often fail to generate ef-
ficient paths due to their complete avoidance of obstacles [1]. This paper proposes a navigation
method that integrates tactile perception with contact modeling [2], [3], employing a linear contact
force modeling approach based on spring-damper characteristics [4], [5], and incorporating it into
tactile-perception-enhanced Cost-Aware RRT* [6] and Informed RRT* [7] path planning algorithms.
A systematic comparison with traditional path planning methods without tactile perception is con-
ducted. Experimental results demonstrate that the proposed method outperforms conventional
RRT* in narrow and unknown environments. To further validate overall performance, a trajectory
tracking controller is designed, and multi-target as well as random scenario tests are carried out on
the H-Man platform [8] and in PyBullet simulation [9]. The results show that tactile-assisted plan-
ning can significantly improve reachability and efficiency while ensuring safety. Moreover, addi-
tional simulation analyses indicate the potential of nonlinear and saturation models under condi-
tions of large deformation, suggesting a future direction for integrating physics-based modeling with
deep learning–based residual compensation.

## Learning to Manipulate from Pixels on Rigid Body Robots with a Kinematic Critic 

This paper introduces a pixel-based actor-critic architecture featuring a differentiable Denavit-Hartenburg (DH) forward kinematics function in the critic sub-network, which achieves substantial improvement in average cumulative reward across several complex manipulation tasks and two robot arms in Robosuite, compared to strong baselines. Forward kinematics as described by DH parameterization for rigid-body robots is fully differentiable with respect to input joint angles, given fixed link-relative geometric information, and including this differentiable module improves training of reinforcement learning agents on an array of benchmark manipulation tasks.  We show the importance of formulating a differentiable kinematic function for overall task performance in an ablation study, and demonstrate a simulation-learned policy running on a real Jaco 7DOF robot. 

Johanna Hansen*, Kyle Kastner*, Yuying Huang, Aaron Courville, Dave Meger, and Gregory Dudek

[![Pitch](https://img.youtube.com/vi/9sShOuqNgAc/hqdefault.jpg)](https://youtu.be/9sShOuqNgAc)

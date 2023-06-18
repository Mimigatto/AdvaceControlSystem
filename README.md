# AdvaceControlSystem
AdvanceControlSystem
Welcome to the Advance Control System repository! This GitHub repository provides a comprehensive implementation of modeling and control techniques for a 3 degree of freedom (DoF) robot with a fixed base. The robot consists of two revolute joints and one prismatic joint, forming a Revolute Prismatic Revolute (RPR) configuration.

### Repository Contents

1. **Modeling:** The robot is modeled using the Denavit-Hartenberg convention, a widely used method for kinematic modeling of robotic systems. The forward and inverse kinematics of the robot are derived using transformation matrices and symbolic equations.

2. **Differential Kinematics:** The repository includes the derivation of the differential kinematics of the robot. Geometrical and analytical Jacobians are employed to analyze the velocities of the robot's end-effector.

3. **Dynamics:** Two different formulations, Lagrange and Newton-Euler, are utilized to obtain the dynamics of the robot. A comparative analysis is provided to evaluate the accuracy and efficiency of each formulation.

4. **Controllers:** Various control strategies are implemented and tested in both joint space and operational space using MATLAB Simulink. The controllers available in this repository include:

   - Proportional-Derivative (PD) Control
   - Inverse Dynamics Control
   - Adaptive Control
   - Direct Force Control
   - Indirect Force Control

5. **Performance Evaluation:** The performance of each controller is evaluated by considering different tasks such as tracking a desired trajectory or applying a desired force. Comprehensive simulations and performance metrics are provided to assess the effectiveness of the implemented control strategies.

### Getting Started

To get started with the Advance Control System repository, follow these steps:

1. Clone the repository to your local machine using the following command:

      git clone https://github.com/mimigatto/AdvanceControlSystem.git
   
2. Install MATLAB and Simulink on your system. Ensure that you have the necessary toolboxes for symbolic calculations and control system design.

3. Open MATLAB and navigate to the cloned repository directory.

4. Explore the different folders and scripts available in the repository to understand the robot modeling, control strategies, and performance evaluation techniques.

### Dependencies

The Advance Control System repository relies on the following dependencies:

- MATLAB (Version R2020a or higher)
- Simulink
- Control System Toolbox
- Symbolic Math Toolbox
- Robotics System Toolbox

Make sure to have these dependencies installed and properly configured before running the code.

### Contributing

Contributions to the Advance Control System repository are welcome! If you have any improvements, bug fixes, or new features to contribute, please follow the standard GitHub workflow:

1. Fork the repository to your own GitHub account.

2. Create a new branch with a descriptive name for your contribution.

3. Commit your changes and push the branch to your fork.

4. Open a pull request on the main repository, explaining the purpose and changes made in your contribution.

### License

The Advance Control System repository is available under the [MIT License](https://github.com/mimigatto/AdvanceControlSystem/blob/main/LICENSE). You are free to use, modify, and distribute the code for personal or commercial purposes.

### Contact

If you have any questions, suggestions, or feedback, feel free to contact the repository maintainer at monruethai.sueksakan_03@studenti.univr.it I appreciate your interest and involvement in the Advance Control System project!

Enjoy exploring and experimenting with the advanced control techniques for the RPR robot in this repository. Happy coding!

![alt text](https://images2.imgbox.com/72/1a/YRJ4OoM5_o.png)

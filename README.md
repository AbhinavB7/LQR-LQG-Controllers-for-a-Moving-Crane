# LQR-LQG-Controllers-for-a-Moving-Crane

The project centers on the control of a crane moving along a one-dimensional track, functioning as a frictionless cart with mass M. The system is actuated by an external force F, serving as the input to the system.

![image](https://github.com/AbhinavB7/LQR-LQG-Controllers-for-a-Moving-Crane/assets/87815926/89e4f922-36a9-476f-ac08-d8a201200f30)

Two loads, denoted as 𝑚 and 𝑚 , are suspended from cables attached to the crane. Each load is associated with specific cable lengths, 𝑙 and 𝑙 , contributing to the complexity of the system dynamics.

The initial focus involves utilizing the Lagrangian method to derive the equations of motion for the entire system. This step leads to the formulation of the non-linear state space representation of the crane and load system.

To facilitate control design, the system undergoes linearization around an equilibrium point.Controllability conditions are then established based on the system parameters 𝑀, 𝑚 , 𝑚 , 𝑙 and 𝑙 , providing essential criteria for subsequent control strategy development.

![image](https://github.com/AbhinavB7/LQR-LQG-Controllers-for-a-Moving-Crane/assets/87815926/bd4aa4ae-e992-4df6-b405-f28866db3363)

With controllability confirmed, an LQR (Linear Quadratic Regulator) controller is designed for the crane and load system. Simulation responses are recorded for both the original non-linear system and the linearized system. Further stability analysis is performed through Lyapunov analysis, ensuring the efficacy of the designed controller. 

Continuing the project, the focus shifts to enhancing system observability by designing Luenberger observers tailored for each observable output vector. These observers aim to estimate internal states based on available output information, ensuring a comprehensive understanding of the system's behavior. Simulations evaluate the Luenberger observers' responses to initial conditions and unit step inputs for both the linearized and original nonlinear systems, providing crucial insights into their performance under various scenarios. 
![image](https://github.com/AbhinavB7/LQR-LQG-Controllers-for-a-Moving-Crane/assets/87815926/a29fb2b2-6b01-4ebd-b4cf-1ebaa0c7c5c6)

![image](https://github.com/AbhinavB7/LQR-LQG-Controllers-for-a-Moving-Crane/assets/87815926/be7a9a7c-198a-44ec-a8ea-510ecd037a19)

In the subsequent phase, an output feedback controller is crafted using the LQG method, emphasizing efficiency in utilizing the "smallest" output vector for control. The designed controller is then applied to the original nonlinear system, and its performance is rigorously examined through simulation. Exploring reconfiguration possibilities, considerations for achieving asymptotic tracking of a constant reference on the x-axis are undertaken. Furthermore, the controller's robustness is assessed against constant force disturbances on the cart, ensuring its effectiveness in real-world applications. This holistic approach aims to provide a well-rounded understanding of the control strategies and their applicability to the dynamic crane and load system.


Contact me for the MATLAB code.

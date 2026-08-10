# Semester project in "Control Engineering for Robotic Systems"

**Technologies:** Qube Servo 3, ROS2, Gazebo, MATLAB, Python, PID, LQR

**Demo video:** https://youtu.be/o5AcVVNCWl8

Modeled, simulated, and controlled a rotary inverted pendulum, comparing a classical
cascade PID controller against a modern LQR controller for balancing and disturbance
rejection.

![[img/qube-servo.png]]

In my fourth-semester project at the University of Southern Denmark, my team and I designed
and implemented control systems for the Qube Servo 3, a two-degree-of-freedom rotary inverted
pendulum. The goal was to stabilize the pendulum upright using both a classical and a modern
control approach, and to compare them through structured testing, including physical
disturbances applied by a UR5 robotic arm.

My role focused on the Gazebo simulation and the classical control design. I worked on the
simulation environment, including the URDF robot model and the ROS2 Control interface tying
the simulated joints to the same effort and state topics used on the physical hardware, letting
the same controller code run in both simulation and on the real robot. On the control side, I
worked on the classical cascade PID controller, using root locus to design an
inner loop stabilizing the pendulum and an outer loop keeping the arm centered.

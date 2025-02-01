# fluid_solver

This is my first pass at a fluid dynamics simulator. The idea is a 2D fluid dynamics simulator that models the behavior of an incompressible fluid interacting with a cylindrical obstacle, using a grid-based approach. The simulator uses the physical principles of advection, pressure solving, and velocity integration. To make this fluid solver, I used Nvidia's Warp Python library and an example program in which Warp is used to simulate an oscillating fluid source. In addition to Warp, I utilized Matthias Müller's video on building an Eulerian fluid simulator to better understand and implement the physics processes involved.

It was cool to see that the physics concepts of the real world can be replicated systematically using math and programming. Also satisfying to see the beautiful animation that gets created! This was fun and I am excited to learn more.

Here is the animation created from my program:

<img src="https://github.com/user-attachments/assets/d08866e6-a8b3-46e4-b161-93e2a743f336" alt="my_fluid_demo" width="500" />

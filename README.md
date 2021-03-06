# SwarmControl
Simulation of a robotic swarm with various methods of human control.

### Controls:
Press numbers 0 - 6 to switch between control modes.
  * 0 is null; no control, drones just drift around.
  * 1 is carrot; carrot can be moved around scene, and swarm follows.
  * 2 is vector based control at swarm COM.
  * 3 is vector based control at center of implied circle w/ optional visualization of the circle.
  * 4 is leader that rest of the swarm flock to -- leader holds the carrot.
  * 5 is leader where carrot drags behind leader at distance based on size of swarm when leader turns, carrot will slowly move to keep being behind the leader.
  * 6 is the above, but the carrot won't stay behind the leader, so it's like the leader is dragging the carrot on a chain.


In control modes 0 and 1, you have direct control over a flying drone.

In this mode: 
  * Use **WASD** or **Arrow Keys** to control the drone movement, and the **mouse** to look around.
  * Use **Q** and **E** to go up and down.
  * Use **CTRL** and **Shift** to slow down or speed up.
  * Press **F** to shoot a ball out of the cannon (which can be used to flip drones)
  * Press **Z** and **X** to change the power that balls are shot out.

In the other control modes, simply use **WASD** or **Arrow Keys** to control the swarm/leader.
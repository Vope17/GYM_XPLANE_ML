## XPlane_ML_Reinforcement_Learning_Autopilot
This project documents set up of Reinforcement learning environment for flight control. This will enable each user/learner/student/flight enthusiast to come with their own RL algorithm that can interact with and control in real time an aircraft in a simulation environment. The simulator used is ***X-Plane*** (the flight environment). This gives a realistic environment to work with together with parameters to keep the simulation as close to reality as possible.


## Requirement
* X Plane (Demo version) (main requirement)
  * [XPLane](https://www.x-plane.com/)
* XPlaneConnect (replace this with  different python udp connection file if required)
  * [XPlaneConnect](https://github.com/nasa/XPlaneConnect) [https://github.com/nasa/XPlaneConnect]
* Tensorforce (Use this to test your algorithm with typical RL Benchmarks)
  *  [Tensorforce](https://github.com/reinforceio/tensorforce) [https://github.com/reinforceio/tensorforce]
* RL Algorithm (defined  your own RL algorithm)
* Lua Programming (for seamless interaction with XPlane)

## General setup

* Multi-agent set up: In this set up, two or more agents can collaborate or compete to achieve a flight path. Again this can be configured in a typical normal LAN set where we have a central system that co-ordinates the activities of other systems. 
* Standalone: On a single x plane for a single user.
* Distributed training environment: This set up uses python flask and celery to achieve distributed training on a large network. 





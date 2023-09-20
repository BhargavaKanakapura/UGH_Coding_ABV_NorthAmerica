# Agent Based Traffic Simulation
In this project, we use an agant based simulation to simulate cars moving through a city. Using the amount of time
that the car takes, we optimized the cycle times of each signal to reduce the time each car spends waiting at red lights.

## Challenges
Understanding how drivers behave in order to hardcode rules of the agents as they navigate the grid was challenging, since
human behavior almost always defies the rules of the road. We simplified the problem based on our driving experiences
in the Bay Area, CA.
- We used a two-lane road all around.
- Inner lanes always turn left.
- Outer lanes always go straight or turn right.
- Cars can merge if they are not waiting at the edge of an intersection. Merging cars take priority over other actions because
  they cut off other cars.

Understanding how to optimize the signals was a huge challenge because we had to create our own optimization method and functions.
For now, we used a rudimentary method of optimizing each signal individually over several epochs.

## Running Our Code
Run in Google Colab.

NOTE: It will take a VERY VERY long time to run an entire simulation.

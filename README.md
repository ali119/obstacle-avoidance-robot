# obstacle-avoidance-robot
Avoid Obstacles
## Code Description
The robot is programmed in C++. The main loop reads the distance from an
ultrasonic sensor. If an obstacle is closer than the safety threshold, the robot
stops, scans left and right, and turns toward the side with more free space.
Otherwise, it drives forward. The decision logic is kept separate from the
hardware code so it can be tested on a PC without the robot.

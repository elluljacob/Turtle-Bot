# Controls
Controls have been implemented as the specification. 'm' switches between
manual and automatic, and 's' always returns the robot to the stopped state in manual movement.

# Setup 
To start solving the maze set the robot facing parallel to the first left wall inside the maze, away from the entrance. It will set that direction as it's relative North and will always follow the left wall. It should be positioned roughly in the centre of the first cell but doesn't need to be exactly centre or exactly parallel.

# Logging 
The maze is logged and generated where the main.py is ran from, the entrance of the maze should appear in row 3 column 0 such that it is facing North. Meaning moving North for the robot corresponds to a decrease in row index, and moving East for the robot corresponds to an increase in the column indee, vice versa for South and West.

# Lidar-Free Movement 
To begin this movement, first set the robot up as described in 'Setup' then while stopped in manual mode press 's' then 'x'. Pressing 's' leads to a confirm state, 'x' confirms the decision to go into lidar-free movement mode and pressing 's' cancels this decision. 's' can be pressed at any time to return to manual mode. 

Once started the robot will move to 2,2 always following the left wall, once it reaches 2,2 it will stop and do a wiggle to signify completion.
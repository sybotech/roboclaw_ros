# Forked on 21/10/2016
Fork of https://github.com/sonyccd/roboclaw_ros
Original driver was buggy.
Added thread to manage both odom and command in the same time. 
WIP, please use at your own risk

# Changes
21/10/2016
Added thread usage for simultaneous odom and command
Watchdog hack using SpeedDistanceM1M2 function 
Inverted l/r motor command
Added Currents feedback on rosdebug

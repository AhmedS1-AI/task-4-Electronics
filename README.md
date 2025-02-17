# task-4-Electronics
![1111111](https://github.com/user-attachments/assets/53249b0d-bece-4b2b-88d9-95c2a65b08c7)


I programmed all the motors to 90 degrees and started installing the legs

Algorithm: Humanoid Robot Walking Motion
Initialize System

Power on the robot.
Calibrate sensors (gyroscope, accelerometer, and force sensors).
Set initial position (standing posture).
Check Balance

Read data from sensors to ensure stability.
Adjust posture if needed using PID control.
Lift One Leg

Shift weight to the support leg.
Slightly bend the knee of the support leg for balance.
Lift the opposite leg by rotating the hip joint forward.
Move Leg Forward

Extend the lifted leg forward.
Adjust foot angle for landing.
Place Foot on the Ground

Lower the leg gradually.
Ensure smooth contact with the ground.
Shift weight to the newly placed foot.
Repeat for the Other Leg

Lift the opposite leg.
Move it forward.
Place it on the ground.
Maintain Balance

Continuously adjust body posture using real-time sensor feedback.
Modify step size and timing if necessary.
Continue Walking

Repeat the process to maintain a continuous walking motion.
Adjust speed and direction based on commands.
Handle Obstacles (if any)

Use vision sensors to detect obstacles.
Stop or step over obstacles accordingly.
Stop Motion

Gradually reduce step length.
Shift weight evenly to both legs.
Return to the standing position.


# 6506-Code-2019-v2
Simplified rewrite of the old CommandBased code with TimedRobot implementation. Far easier to debug on the fly (read: actually readable).

# CONTROLS:
- LJoystick - Move
- RJoystick, vertical - Lift/lower arm
- L**bumper**: Intake ball
- R**bumper**: Outtake ball

# NOTES:
- Code does not check for arm positioning. Please be wary when lowering arm all the way down as the motor *will not stop*.
- Former controls were A for Ascend, B for  **B** escend. These were deprecated at Champs in favor of analog controls.
- Similarly, the intake used to use the triggers. Buttons were easier to implement as they didn't require a wrapper class. Don't know why we used them in the first place.
- Thanks to the FTA who helped us w/ this.
- I forgot to upload this the entire summer. Sorry Noah.

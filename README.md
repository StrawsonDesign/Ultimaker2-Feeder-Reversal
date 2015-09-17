This is a fork of the Ultimaker 2 firmware to demonstrate reversing of the 
feeder motor. This is necessary when flipping the direction of the
feeder mechanism to reduce friction.

See Feeder_Orientation.jpg to see how to properly mount the feeder mechanism.
The intention is for the knurled feeder wheel to apply pressure to the 
inside on the filament's natural bend instead of the outside. This keeps
the outside of the bend smooth and significantly reduces the friction
in the bowden tube.

This simple flip displayed a threefold increase in extrusion capacity
over the factory orientation due to reduced friction. 

See Speed_Improvement_Test.jpg for the results. The test was conducted on
two Ultimaker 2 printers simultaneous before and after both had the 
feeder reversal mod and software update to the reverse the motor. One ran
blue PLA and the other ran white PLA. Both at 210 degrees for each test.

With the factory orientation of the feeder each printer was only able to
print at 3mm^3/s without errors or feeder skips. After the feeder reversal
each printer was able to print at 9mm^3/s.

Also note that this is with the stepper motor current set to 1300ma.
I also have the feeder spring tension gauge set all the way to the top. 
Any extra tension seems to chew up the filament and cause jamming.

See Strawson's Ultimaker Settings.fff for the SImplify3D settings I
use with this configuration. You will notice a 1.02 extrusion multiplier
is used instead of default 1.10 as less slip now occurs due to reduced
friction. The print speed is also conservatively set at 50mm/s although
I have printed as fast as 75.
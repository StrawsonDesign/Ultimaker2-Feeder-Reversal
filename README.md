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
two Ultimaker 2 printers simultaneous before and after both went the 
feeder reversal and software update to the reverse the motor. One ran
blue PLA and the other ran white PLA. Both at 210 degrees for each test.

With the factory orientation of the motor each printer was only able to
print at 3mm^3/s without errors or feeder skips. After the feeder reversal
each printer was able to print at 9mm^3/s.

Also note that this is with the stepper motor current set to 1350ma.
I also have the feeder spring tension gauge set all the way to the top. 
Any extra tension seems to chew up the filament and cause jamming.
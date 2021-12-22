# ObjectsLeavingSun
This code simulates the motion of 1000 objects being ejected from the Solar System. This was made with the intention of eventually applying
it to other star systems. In order to do this, simply change the Orbit used to initialize the "o" orbit. 

This code relies heavily on @jobovy's galpy. It also uses a package called Celluloid in order to make animations. 

The positions and velocities of each of the objects at each of the times in timesList is stored. Simply call from one of the following 2d numpy arrays: xPositionsAll, yPositionsAll, zPositionsAll, rPositionsAll, xVelocitiesAll, yVelocitiesAll, zVelocitiesAll.

For example, "xPositionsAll[objNum][t]" gives the x position of object objNum at time t in timesList.

# pz-acq
This script is used to change the pole zero value in the OBD as well as change the comment to document which pz was used for which run. 
Then it waits 4 min to allow everything to update properly
It starts the run then waits for 180 seconds (if the run you're taking is longer than this you will need to update it to a period longer than the run)
It will restart and cycle through all the pz values in arr

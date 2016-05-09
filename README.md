# 3rdArm-BCI

Original 3rd Arm maxpatches created by Roozbeh Khodambashi at the Georgia Tech Center for Music Technology 
(* indicates that the maxpatch was modified from its original state):

3 Motor Trajectory Follower.maxpat

averagingFilter.maxpat

readTrajectoryData.maxpat

wireless1.maxpat

*everythingTogetherLookingNice1.maxpat



Maxpatches created for EEG-BCI-SSVEP Project:

EEG_3rdArm.maxpat

lua.maxpat


everythingTogetherLookingNice1.maxpat was modified to include hardcoded positions values for the snare and ride cymbals that were triggered by the BCI.

EEG_3rdArm.maxpat is the main demo patch that receives commands from the BCI and sends commands to the patch controlling the arm. It uses counters to deal with the high false positive rate.

lua.maxpat is not needed to run the demo- it's a test patch that receives the messages from Lua directly


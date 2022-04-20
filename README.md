# GainAdaptation
This repository contains experimetal data in the format of MATLAB files used in Ikegami et al.'s paper "Reach adaptation to a visuomotor gain with terminal error feedback involves reinforcement learning". MATLAB needed to be installed to open the data files.

Each mat file contains a table ('TrialData') containing the data of each participant in the experiment (from the training phase to the transfer phase). The prefix of the file name indicate the group (EC, ET, or R).

TrialData contains the following variables-

TrialNumber: 	 trial number

Phase:		     experimet phase (1 = training, 2 = generalization, 3 = post-generalization, 4 = transfer)

TrialType:		 trial type (1 = training trial, 2 = probe trial)

Gain:  		     visuomotor gain (increased slowly from 1 to 1.33 in increments of 0.167 every 15 trials)

Target: 		   target direction: 0° (forward reaching direction), ±22.5°, ±45°, ±90°, and 180° (positive angles defined as clockwise)

ReachDistance: hand reach distance (cm)

ExcludedTrial: trials excluded from the analysis of generalization function (0 = included trial; 1 = excluded trial)

Hello,
This repository contains all Maple worksheets that have been used in "Many-revolution Earth-centred solar-sail trajectory optimisation using differential dynamic programming", G. Leemans, L. Carzana, J. Heiligers, 2021.

STMsIJKtoMEE -> all derivatives to transform the dynamics matrix and tensor from Cartesian coordinates to Modified Equinoctial Elements
costFunction_orbitalEnergy -> derivatives of the optimal cost-to-go needed at the final stage, when the original objective is the specific orbital energy
satellite_j2 -> derivatives of the accelerations due to the J2 effect w.r.t. the augmented state vector
satellite_j3 -> derivatives of the accelerations due to the J3 effect w.r.t. the augmented state vector
satellite_j4 -> derivatives of the accelerations due to the J4 effect w.r.t. the augmented state vector
satellite_lunar -> derivatives of the accelerations due to the lunar gravity w.r.t. the augmented state vector
satellite_solar -> derivatives of the accelerations due to the solar gravity w.r.t. the augmented state vector
satellite_twobody -> derivatives of the accelerations due to point-mass gravity from the Earth w.r.t. the augmented state vector
satellite_solarsail -> derivatives of the accelerations due to the solar sail w.r.t. the augmented state vector
satellite_eclipsefunction -> derivatives of the accelerations due to the solar eclipse w.r.t. the augmented state vector 
sundman_eta -> derivatives of the Sundman transformation needed to transform the STMs
sun_sunchronous_constraint -> derivatives of the optimal cost-to-go needed at the final stage when the sun-synchronous constraint is used

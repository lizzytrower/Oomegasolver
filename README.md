# Oomegasolver

This set of Matlab codes is an application of work from Trower et al. (2017) to estimate carbonate saturation state (Omega) of ancient seawater or lake water using measurements of ooid size. "Oomega" is a combination of "ooid" and "Omega".
The oomegasolver.m file is a Matlab function that accepts inputs that describe ooid size, transport mode and frequency, and carbonate precipitation kinetics, and outputs estimated Omega.
The susp_abrasion_calculations_abrcalc.m is a script that is run by the Oomegasolver function and should not be edited by the user.
IMPORTANT: The code as written is not designed for vectors as inputs; I recommend running it with a for-loop if you have a large set of grain sizes that you want to calculate Omega estimates for.
Required units of inputs are described in comments in oomegasolver.m

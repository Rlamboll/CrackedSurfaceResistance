# CrackedSurfaceResistance
Matlab script that finds the resistance of a 2D surface with cracks in it. 

Originally coded to allow the calculation of the resistance of a cracked gold nanoparticle film upon extension of the film. 
In this case, the SEM image is binarised and then used to calculate the resistance. Workflow: 'binariseImage', then 'VoltageAndResistanceCalc' on the output of that and 'calcI' last if we wish to visualise the currents. 

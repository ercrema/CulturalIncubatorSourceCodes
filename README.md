# CulturalIncubatorSourceCodes
Source Codes, Scripts, and outputs for the paper "Cultural Incubators and Spread of Innovation" by Enrico R. Crema and Mark W. Lake

**Authors**:

*Enrico R. Crema*  CaSEs Research Group - Department of HUmanities Universitat Pompeu Fabra (UPF) & UCL Institute of Archaeology, email: enrico.crema@gmail.com

*Mark W. Lake* UCL Institute of Archaeology, email: mark.lake@ucl.ac.uk

All Codes written in R (version 3.1.2), Required Packages: utils 3.1.2; foreach 1.4.2; doParallel 1.0.8; tgp 2.4.11

**File Structure**


* ./[src.R] (https://github.com/ercrema/CulturalIncubatorSourceCodes/blob/master/src.R)  --> Contains main source code for running all simulations

* ./[experiment1] (https://github.com/ercrema/CulturalIncubatorSourceCodes/blob/master/experiment1) --> Folder containing scripts for executing experiment 1 (experiment1.R) as well as the output used in the paper (experiment1.RData)

* /experiments2_3

   * ./experiments2_3/prepareSweep.R  --> script for creating a parameter combinations using Latin HyperCube Sampling
    
   * ./experiments2_3/sweepExp2.RData --> parameter combinations used for experiment 2, generated with prepareSweep.R 
    
   * ./experiments2_3/sweepExp3.RData --> parameter combinations used for experiment 3, generated with prepareSweep.R 
    
   * ./experiments2_3/submit_``*`` --> script for executing experiments 2 & 3. Notice that this was originally conducted on a cluster as an array job. The scripts are thus not the original codes used to generate the simulation outputs but for illustrattive purpose, showing both a single-threaded version (to be executed on a local machine) and an array version (to be executed on a cluster). 
    
   * ./experiments2_3/results --> folder containing .csv files of the simulation outputs for experiments 2 & 3.
    
    
  ***
    
    
    
    

# fringeAsteroids
Find main-belt asteroids suitable for MIRI-MRS fringe characterization within a given time frame, within a range of diameters, and larger than a user-specified minimum flux at different wavelengths.

This script relies, among a few standard packages installable via conda, on https://github.com/MigoMueller/NEATM for modeling the mid-IR emission of asteroids. 
Also, the NEOWISE catalog of asteroid diameters is required.  It can be downloaded from https://sbn.psi.edu/pds/resource/neowisediam.html (we're using v2.0, released 2019-03-11) - unzip the file neowise_diameters_albedos_V2_0.zip into the working directory of the notebook.

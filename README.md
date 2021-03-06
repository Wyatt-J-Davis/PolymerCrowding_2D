# DPM

## Description
DPM (Disk-Polymer Mixture) is a Monte Carlo simulation developed by Wyatt Davis and Dr. Alan Denton at North Dakota State University to probe the influence of macromolecular crowding on chain polymer conformation when the mixture is confined to a plane. Our coarse-grained modeling approach can be characterized as follows: chain polymers are represented by soft ellipses that fluctuate in size/shape according to random walk statistics and crowders are represented by hard disks.

See demo [here](https://drive.google.com/file/d/1byAPYyyXBgtaFtDYFWWCoRVHRhXHQTuM/view?usp=sharing)

## Instructions
1. Place source code within directory: osp_project/src/org/opensourcephysics/sip/DPM 
2. Compile and run code from osp_project/ directory using a bash script 
3. Specify run parameters using GUI  
4. Simulation will create directory within osp_project/data/ with a name that cooresponds to run parameters and write raw gyration tensor eigenvalue data for five independant runs within directory
5. It is up to the user to analyze raw geometric data in meaningful way. I recommend writing a custom data analysis script in python. 

## Requirements
- [JDK 1.8](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
- [Open Source Physics Library](https://www.compadre.org/osp/)


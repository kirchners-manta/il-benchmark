# il-benchmark

"Lessons learned on obtaining reliable dynamic properties for ionic liquids", *ChemPhysChem* (currently under review).

The data is organized in the following way:

In the [inputs](./inputs/) folder, you will find the LAMMPS input files used to run the simulations. 
The subdirectories are named according to the force field used in the simulations: [standard CL&P](./inputs/CLP/), [charge-scaled CL&P](./inputs/CLP-chrgscl-08/), [polarizable CL&Pol](./inputs/CLPol/), and [NGOLP](./inputs/NGOLP/).
Each simulation directory has subdirectories named according to the number of ion pairs in the simulation and contains another directory named `siminp` with the input files for the LAMMPS simulations (no need to change anything in these files).
The additional subdirectory `extra` contains additional inputs that can be used to create the input files for the simulations by hand, using [fftool](https://github.com/paduagroup/fftool).
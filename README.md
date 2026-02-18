# ISIS-Xsuite
Xsuite model for vertical traverse instabilities in the ISIS Neutron and Muon Source Rapid Cycling Synchrotron
This repository provides Python code to simulate transverse beam dynamics in the ** ISIS Rapid Cycling Synchrotron** using Xsuite.

The model implements the full vertical impedance:

Thick resistive wall
Five dipolar resonator terms
The script can track single or multiple Gaussian bunches turn-by turn and generated HDF5 output files containing bunch and slice statistics. Example analysis plots (spectrogram, head-tail profiles, and tune spectra) are also included.

Requirements
Python > 3.9

Packages:

```pip install numpy pandas matplotlib scipy h5py xtrack xpart xwakes```

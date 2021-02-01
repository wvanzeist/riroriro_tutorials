# riroriro_tutorials
This repository houses tutorials for the gravitational wave-simulating package Riroriro. https://github.com/wvanzeist/riroriro

The following tutorials are included:
- example_GW, on using Riroriro to generate a synthetic gravitational wave signal for a binary black hole merger
- example_SNR_findchirp, on using Riroriro to calculate the signal-to-noise ratio (SNR) of the gravitational waveform from a given binary merger
- example_horizon, on using Riroriro to calculate horizon distances and detectability percentages for a given merger

Full documentation of each of the functions of Riroriro can be found here: https://github.com/wvanzeist/riroriro/tree/master/docs/riroriro

The "example_SNR_findchirp" tutorial uses pre-generated findchirp_array data which can be found at the following link: https://drive.google.com/drive/folders/12TYxYKtBL1iuFHG_ySFhS12Aqv4JHGOr In each filename, the first number is log(Mc) and the second is the mass ratio q.

The files “example_1.4_0.8” and “example_1.4_0.8_withpol” are example Riroriro output and the “noise_spectra” files are LIGO/Virgo detector noise spectra (from https://dcc.ligo.org/LIGO-T1500293/public); these are included in this repository for use with the tutorials and Riroriro’s unit tests.
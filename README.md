# riroriro_tutorials
This repository houses tutorials for the gravitational wave-simulating package Riroriro. https://github.com/wvanzeist/riroriro

The following tutorials are included:
- example_GW, on using Riroriro to generate a synthetic gravitational wave signal for a binary black hole merger
- example_SNR_findchirp, on using Riroriro to calculate the signal-to-noise ratio (SNR) of the gravitational waveform from a given binary merger
- example_horizon, on using Riroriro to calculate horizon distances and detectability percentages for a given merger

The directory “findchirp_traces” contains generated findchirp_arrays for use with Riroriro’s snrcalculatorfuns module. In each filename, the first number is log(Mc) and the second is the mass ratio q.
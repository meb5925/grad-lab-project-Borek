# Analysis of Temporal Dynamics of Chromatic Aberration in the Human Eye

Megan Borek

This project investigates how chromatic cues influence the temporal dynamics of human accommodation. A Shack–Hartmann wavefront sensor measures the eye’s wavefront while participants view stimuli that vary in optical distance and modulate contrast in specific retinal cone types.

The analysis uses Zernike-derived defocus to calculate accommodation gain, the ratio of the eye’s response amplitude to the stimulus amplitude. It compares gain across temporal frequencies, stimulus types, and cone-contrast conditions.

## Analysis Inputs and Tools
- Output CSV files containing defocus measurements over time
- MATLAB struc files containing trial conditions, stimulus frequencies, and commanded stimulus amplitudes
- MATLAB for data processing, analysis, and plotting

## Analysis Tasks:
- [x] Sort data by trial type
- [x] Extract relevant Zernike coefficients (defocus aberration) from output CSV files and plot as a function of time
- [x] Calculate the FFT and plot gain as a function of stimulus frequency

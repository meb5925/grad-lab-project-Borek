# Analysis of Temporal Dynamics of Chromatic Aberration in the Human Eye

Megan Borek

This project investigates how chromatic cues influence the temporal dynamics of human accommodation. A Shack–Hartmann wavefront sensor measures the eye’s wavefront while participants view stimuli that vary in optical distance and modulate contrast in specific retinal cone types.

The analysis uses Zernike-derived defocus to calculate accommodation gain, the ratio of the eye’s response amplitude to the stimulus amplitude. It compares gain across temporal frequencies, stimulus types, and cone-contrast conditions.

## Analysis Inputs and Tools
- Output CSV files containing defocus measurements over time
- MATLAB struct files containing trial conditions, stimulus frequencies, and commanded stimulus amplitudes
- MATLAB for data processing, analysis, and plotting

## Analysis Tasks:
- [x] Sort data by trial type
- [x] Extract relevant Zernike coefficients (defocus aberration) from output CSV files and plot as a function of time
- [x] Calculate the FFT and plot gain as a function of stimulus frequency

## Next steps
- Upload completed project code to repo


## Reflection
- A commit is the act of creating a "snapshot" which records changes and what your code files look like at a certain point in time. A commit contains information about what changed, a reference to the parent commit, and a hash code name.
- Branching is useful because making changes in a branch from the main code base is safer than making changes directly to main. This is especially true when multiple people are working in the same code base, where changes can create merge conflicts if two people are attempting to make changes in the same areas of code. Branching also allows you to test experimental code while maintaining a stable main version.
- An issue describes and tracks a problem in the code, while a pull request is an avenue for reviewing and merging proposed code to fix the issue. A pull request does not necessarily have to be associated with an issue. 

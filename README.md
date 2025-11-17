# biosignal-processing-project
A MATLAB and Graphical analysis of a given signal, analysis done using Fourier Transformation and band-pass filtering to remove low hertz interference. 
This is my first Github project, an extra-credit optional assignment I did in my intro to BME computing. 

---

## Overview of Project

This assignment and project does the following: 
-Loads and with graphs visualizes the ('Mystery_Signal.mat') file
-Uses FFT BUILT-IN MATLAB function to find "important frequencies"
-Frequency-domain filter, for specific frequency bands in the signal 
-manual DFT using MATLAB 'for loops' 
-Comapre manual DFT with FFT MATLAB function 

## Project Structure 
/plots - contains bandpass filter MATLAB plot and DFT vs MATLAB FFT comparison plot 
/Biosingal-assignemnt - contains MATLAB script for assignment 
/Mystery_Signal.mat - Raw MATLAB data used for assignment


## How to Run 
1. Install MATLAB (if not already installed)
2. Clone or download repository
3. Ensure following files in same folder
  * Mystery_Signal.mat
  * Biosignal_assignment
4. Open MATLAB and navigate to appropriate folder
5. Run script
6. The script should do the following
- Load "Mystery_Signal.mat
- Compute FFT
- Filter the selected frequencies found from FFT
- DFT using FOR LOOPS 
- Then compare FFT and DFT 

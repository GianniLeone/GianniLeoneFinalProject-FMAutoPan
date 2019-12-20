# GianniLeoneFinalProject README
 
 This program is an adaptation of Akitos AutoPanner. 

 The program is capable of automaticaly panning an audio signal along the path of a sine wave. Additionally, the original signal may now be modulated by another sine wave.

 All of the paramaters to be varied are defined in line 12-19.

 The paramater functions are defined bellow.


kInputFileName: Name of .wav file to be read (must be included in file path).
kOutputFileName: Name of .wav file to be written.
kDepth: Sets the carriers pan depth.
kRate: Sets the carriers pan speed in Hz.
kGain: Sets over all signal gain.
kNumChannels: Define number of audio channels.
kModDepth: Sets the modulators depth.
kModRate: Sets the modulators speed in Hz.


Once paramaters are set, the program can be compiled and run with commands:

//Compile with:
//gcc 3.AutoPanning.c -o 3.AutoPanning -lsndfile
//Run with:
//./3.AutoPanning


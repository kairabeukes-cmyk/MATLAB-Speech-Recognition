# MATLAB Speech Recognition Application

A MATLAB application developed as a university signal processing project to record, analyse and identify spoken words.

## Overview
The application uses audio recording, frequency-domain analysis and numerical feature comparison to identify spoken words from a reference database.

## Technologies
- MATLAB
- Digital signal processing
- Fast Fourier Transform (FFT)
- Blackman windowing
- Euclidean distance classification

## Key Features
- Recording and storing speech samples
- Building a reference database of recorded words
- FFT-based frequency analysis
- Extracting frequency-band energy features
- Comparing input recordings with reference samples
- Identifying the closest matching word and speaker

## How It Works
1. Record reference speech samples.
2. Apply a Blackman window and calculate the FFT.
3. Extract frequency-band energy features.
4. Store reference features in a database.
5. Record an unknown speech sample.
6. Compare its features using Euclidean distance.
7. Display the closest matching word and speaker.

## Running the Application
Open the main MATLAB script or App Designer file, ensure the required supporting files are accessible, and run the application. A working microphone may be required.

## Screenshots
Add images of the application interface, FFT visualisation and identification results.

## Project Context
Developed as part of university coursework to apply digital signal processing and MATLAB programming techniques.

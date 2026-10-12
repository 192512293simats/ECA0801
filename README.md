# ECA0801 - Analog and Digital Communication

This repository contains MATLAB simulations for **20 experiments**
related to Analog and Digital Communication (ADC). The experiments cover
analog modulation, noise analysis, quantization, digital modulation,
channel effects, error-control coding, spread-spectrum communication,
and cellular communication.

## Experiments

### 1. Characteristics Study of Sideband Power and Frequencies in AM Using MATLAB

-   Generates the message signal, carrier signal, AM-modulated signal,
    and demodulated signal.
-   Displays the AM frequency spectrum and compares carrier,
    upper-sideband (USB), and lower-sideband (LSB) power.
-   Demonstrates modulation index, sideband frequencies, and AM power
    distribution.

### 2. MATLAB-Based Modelling of VSB Modulator and Demodulator for Analog Television Communication Applications

-   Generates message and carrier signals.
-   Models DSB-SC modulation followed by filtering to obtain the
    simulated vestigial sideband (VSB) signal.
-   Performs coherent demodulation and low-pass filtering to recover the
    message.
-   Plots the message, carrier, DSB-SC, VSB, and recovered signals.

### 3. MATLAB Simulation of Superheterodyne Receiver for AM Communication System with Frequency Mixing and Filtering

-   Generates the message, carrier, and AM signals.
-   Mixes the AM signal with a local-oscillator signal to produce
    frequency components.
-   Applies intermediate-frequency (IF) filtering.
-   Uses envelope detection to display the recovered signal.

### 4. Generation and Analysis of Frequency Modulated (FM) and Phase Modulated (PM) Signals Using MATLAB

-   Generates a message signal and carrier signal.
-   Simulates FM and PM signals.
-   Plots the signals for comparison.

### 5. Calculation and Verification of Frequency Deviation and Modulation Index of FM Signals Using MATLAB Simulation

-   Calculates frequency deviation and FM modulation index from the
    specified parameters.
-   Displays the calculated values and supports analysis of FM
    modulation.

### 6. Power Spectral Density (PSD) Analysis of Phase Modulated (PM) Signals Using MATLAB

-   Generates a message signal and a phase-modulated signal.
-   Computes the FFT-based frequency spectrum and power spectral density
    (PSD).
-   Estimates the bandwidth and plots the message, PM signal, frequency
    spectrum, and PSD.

### 7. Performance Evaluation of AM Generation and Detection Under Noisy Channel Conditions Using MATLAB

-   Generates message, carrier, and AM signals.
-   Adds additive white Gaussian noise (AWGN) to the AM signal.
-   Uses envelope detection to obtain the recovered signal.
-   Plots the original signals, noisy AM signal, and recovered signal.

### 8. Performance Analysis of FM System Under Gaussian White Noise Using MATLAB

-   Generates message and carrier signals and creates an FM signal.
-   Adds Gaussian white noise to the FM signal.
-   Plots the message, carrier, FM signal, and noisy FM signal.

### 9. Simulation and Analysis of Uniform and Non-Uniform Quantization Using MATLAB

-   Generates an input sinusoidal signal.
-   Performs uniform quantization using a finite number of levels.
-   Applies μ-law compression-based non-uniform quantization.
-   Plots and compares the original and quantized signals.

### 10. Performance Evaluation of Digital Communication Systems Using Eye Diagram Analysis Under Additive White Gaussian Noise (AWGN) Using MATLAB

-   Generates random binary data and encodes it using an NRZ
    representation.
-   Passes the transmitted signal through an AWGN channel.
-   Plots the input data, transmitted signal, and received noisy signal.
-   Displays the eye diagram of the received signal.

### 11. MATLAB Simulation and Evaluation of Eye Diagram Parameters Under Inter-Symbol Interference in Digital Communication Systems

-   Generates random binary data and an NRZ signal.
-   Models channel effects using a simple low-pass FIR filter to
    introduce inter-symbol interference (ISI).
-   Plots the transmitted and received signals and the eye diagram under
    ISI.

### 12. Simulation and Analysis of BPSK Modulation Using Constellation Diagrams in MATLAB

-   Generates random binary data and maps bits to BPSK symbols.
-   Adds AWGN to the modulated symbols.
-   Plots the input binary data and received BPSK constellation.

### 13. Performance Evaluation of 8-QAM and 16-QAM Communication Systems Under AWGN Using BER, Constellation and Eye Diagram Analysis in MATLAB

-   Simulates 16-QAM modulation and demodulation.
-   Adds AWGN and calculates the bit error rate (BER).
-   Plots transmitted and received constellation diagrams and an eye
    diagram.

### 14. MATLAB Simulation of Passband Transmission with BER Analysis Under Multipath Fading Channels

-   Generates random bits and maps them to BPSK symbols.
-   Models a multipath channel using a discrete filter and adds AWGN.
-   Detects received bits and calculates BER.
-   Plots the transmitted signal, received signal, and a comparison of
    original and detected bits.

### 15. Simulation of Convolutional Codes and Analysis of Encoded Output Bit Sequences Using MATLAB

-   Generates an input bit sequence.
-   Encodes the sequence using a rate-1/2 convolutional code with
    constraint length 3.
-   Displays the input and encoded bits and plots both sequences.

### 16. MATLAB Simulation of Single-Bit Error Detection and Correction Using Syndrome Vectors in Linear Block Codes

-   Encodes a message using a (7,4) Hamming code.
-   Introduces a single-bit error into the codeword.
-   Decodes the received codeword to recover the message.
-   Displays and plots the encoded and corrupted codewords.

### 17. Calculation of Processing Gain and Generation of PN Sequences for Spread Spectrum Communication Using MATLAB Simulation

-   Calculates processing gain from the data rate and chip rate.
-   Converts the processing gain to decibels.
-   Generates and plots a pseudo-noise (PN) sequence.

### 18. Simulation of DSSS Communication System with PN Code Generation and Signal Recovery Using MATLAB

-   Converts binary data to bipolar symbols.
-   Spreads the data using a PN sequence.
-   Despreads the signal and recovers the original data.
-   Displays the original data, spread signal, and recovered data.

### 19. Simulation and Analysis of GSM Communication System with Time Division Multiple Access (TDMA) Using MATLAB

-   Defines bit sequences for four GSM users.
-   Combines the user sequences into a TDMA frame.
-   Displays the TDMA frame and plots the frame bits and TDMA signal.

### 20. Analysis of Cellular Frequency Planning and Handover Performance Under User Mobility Conditions Using MATLAB

-   Defines three cell-center positions and a moving user's positions.
-   Assigns the user to the nearest cell center.
-   Displays the user position and connected cell.
-   Plots handover performance and cellular frequency planning.

## Requirements

-   MATLAB or MATLAB Online.
-   Some experiments use toolbox functions such as `awgn`, `eyediagram`,
    `qammod`, `qamdemod`, `convenc`, `encode`, and `decode`.
    Availability depends on the MATLAB toolboxes installed or enabled in
    your environment.
-   Experiments that use toolbox functions may require the relevant
    Communications Toolbox or Signal Processing Toolbox.

## How to Run

1.  Open MATLAB or MATLAB Online.
2.  Open the `.m` script for the experiment you want to run.
3.  Make sure any required MATLAB toolboxes are available.
4.  Run the script.
5.  View the generated plots and any values displayed in the Command
    Window.

## Repository Contents

-   MATLAB `.m` scripts for the experiments.
-   Generated plots and simulation outputs, where included.

## Author

**Lokesh A (192512293)**\
B.E. Electronics and Communication Engineering (ECE)

## Subject

**ECA0801 - Analog and Digital Communication**

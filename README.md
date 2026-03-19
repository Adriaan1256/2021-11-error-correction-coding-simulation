# Error Correction Coding Simulation using Linear Block Codes and Convolutional Codes

Course – Practical Assignment  
University of Pretoria  
Completed: November 2021  

---

## Project Overview

This project involves the development of two simulation platforms to encode and decode modulated information transmitted through an Additive White Gaussian Noise (AWGN) channel without multipath.

The first simulation platform implements a variation of Linear Block Codes, specifically Low-Density Parity Check (LDPC) codes. The second platform implements Convolutional Codes decoded using the Viterbi MLSE algorithm.

Both simulation platforms use previously developed functionality for bit generation, noise addition, bit-to-symbol mapping, and bit detection. Simulations are performed using BPSK, QPSK, and 8PSK modulation schemes.

The performance of the encoding techniques is evaluated by calculating and plotting the Bit Error Rate (BER) as a function of Signal-to-Noise Ratio (SNR), and comparing the results to uncoded detection.

👉 [View Full Project Report (PDF)](docs/EDC310_Practical_Assignment_3.pdf)

---

## Objectives

- Develop two simulation platforms for encoding and decoding modulated information through an AWGN channel without multipath 
- Implement Linear Block Codes using a variation of LDPC codes 
- Implement Convolutional Codes using a shift register and Viterbi MLSE decoding algorithm 
- Simulate transmission using BPSK, QPSK, and 8PSK modulation schemes 
- Plot BER as a function of SNR to compare encoding schemes 
- Evaluate and compare the performance of Linear Block Codes, Convolutional Codes, and uncoded detection 

---

## Tools & Technologies

- Python 
- NumPy  
- Matplotlib  

---

## Notes

This repository contains the academic report for the project.  

The implementation code used for the simulations (including Linear Block Code and Convolutional Code implementations) is included in the appendix of the report.

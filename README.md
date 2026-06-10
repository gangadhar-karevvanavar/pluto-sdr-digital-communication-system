# End-to-End Digital Communication System using Pluto SDR

This repository contains implementation codes and experiments developed for the **Digital Communication Laboratory** using **ADI Pluto SDR**. The project demonstrates the complete implementation of an end-to-end wireless communication system, including source coding, channel coding, modulation, synchronization, demodulation, decoding, and performance evaluation.

The implementation is designed for hands-on learning of practical digital communication systems and software-defined radio (SDR) concepts.

---

## Project Overview

The communication system is implemented block-by-block using Pluto SDR and Python/MATLAB-based signal processing modules. The project covers both transmitter and receiver chains and explores multiple improvements over a basic communication setup.

The implemented system includes:

- Source coding and decoding
- Channel coding and error correction
- Digital modulation and demodulation
- Pulse shaping and matched filtering
- Carrier and timing synchronization
- Frame synchronization
- Error detection and evaluation
- Real-time SDR transmission and reception using Pluto SDR

---

# System Architecture

## Transmitter Side

### Source Coding
- Text to ASCII conversion
- ASCII to binary conversion
- Huffman coding for compression

### Channel Coding
- Hamming coding for error correction

### Modulation
- BPSK modulation
- QAM modulation

### Preamble and Framing
- Barker sequence generation
- Frame construction

### Pulse Shaping
- Square pulse shaping
- Raised cosine pulse shaping

---

## Receiver Side

### Signal Quality Improvement
- Matched filtering

### Synchronization
- Coarse frequency synchronization using FFT
- Fine frequency synchronization using Costas loop
- Time synchronization and clock recovery
- Mueller and Muller timing recovery

### Frame Synchronization
- Barker correlation based synchronization

### Demodulation
- BPSK demodulation
- QAM demodulation

### Decoding
- Hamming decoding
- Huffman decoding
- Binary to ASCII conversion

### Evaluation
- Bit error analysis
- CRC-based validation
- Decoded text verification

---

# Hardware Platform

- ADALM-PLUTO SDR
- USB interface for SDR communication
- Wireless over-the-air transmission experiments

---


# Implemented Communication Blocks

| Module | Techniques |
|---|---|
| Source Coding | ASCII, Huffman Coding |
| Channel Coding | Hamming Code |
| Modulation | BPSK, QAM |
| Pulse Shaping | Square Pulse, Raised Cosine |
| Synchronization | FFT Estimation, Costas Loop, Mueller & Muller |
| Frame Synchronization | Barker Sequence Correlation |
| SDR Platform | Pluto SDR |

---


# Learning Objectives

This project helps understand:

- Practical digital communication systems
- Software-defined radio implementation
- Synchronization challenges in wireless systems
- Error correction coding
- Real-time signal processing
- End-to-end SDR system design

---

# Learning Resources

### PySDR: A Guide to SDR and DSP using Python
https://pysdr.org/content/intro.html

# Pluto SDR Resources

### Analog Devices Pluto SDR
https://www.analog.com/en/resources/evaluation-hardware-and-software/evaluation-boards-kits/adalm-pluto.html

### PyADI-IIO
https://github.com/analogdevicesinc/pyadi-iio

---

# Sample Experiments

- Text transmission over wireless channels
- BER analysis under noise
- Comparison of BPSK and QAM
- Effect of pulse shaping
- Timing synchronization performance
- Channel coding gain analysis

---

# Future Extensions

Possible future improvements include:

- OFDM implementation
- LDPC and Polar coding
- Adaptive modulation
- MIMO communication
- Semantic communication
- Deep learning based synchronization

---

# Acknowledgment

This repository was developed as part of the Digital Communication Laboratory using Pluto SDR for practical SDR-based communication experiments.


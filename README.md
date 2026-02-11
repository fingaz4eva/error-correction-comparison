Signal Resilience Simulator
Introduction

Digital communication systems are vulnerable to noise and interference. Error correction codes are used to improve reliability. This project compares Hamming (7,4) and Reed–Solomon codes under noisy channel conditions.

Problem Statement

How do different error correction schemes perform under increasing noise levels?

We evaluate performance using:

Bit Error Rate (BER)

Signal-to-Noise Ratio (SNR)

Methodology

Generate random binary data

Apply Hamming and Reed–Solomon encoding

Simulate noise using AWGN

Decode received data

Compute BER

Compare performance across SNR values

Results

Hamming performs well at low noise levels

Reed–Solomon significantly outperforms Hamming at moderate to high noise

RS handles burst errors more effectively

(Add your BER plot image here)

Key Concepts
What is BER?

Bit Error Rate (BER) is the ratio of incorrect bits received to total bits transmitted.

Why RS Outperforms Hamming

Hamming corrects single-bit errors

RS corrects multiple symbol errors

RS is more resilient in burst noise environments

Trade-Offs
Hamming	Reed–Solomon
Low complexity	Higher complexity
Fast	More computational load
Limited correction	Strong correction
Applications

Satellite communication

Wireless systems

QR codes

Data storage systems

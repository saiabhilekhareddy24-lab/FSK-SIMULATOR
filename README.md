FSK Simulator
Overview

The FSK (Frequency Shift Keying) Simulator is a web-based educational project that demonstrates how digital binary data can be transmitted using Frequency Shift Keying modulation.

In FSK, two different carrier frequencies are used to represent binary 0 and 1. The simulator generates the corresponding FSK waveform and performs basic demodulation to recover the original binary data.

Features
Enter a custom binary sequence.
Select frequencies for binary 0 and 1.
Generate an FSK-modulated waveform.
Display the original binary data.
Display the FSK signal graphically.
Perform FSK demodulation.
Compare transmitted and recovered data.
Run test cases using the testbench.
Works directly in a modern web browser.
No external libraries are required.
FSK Principle

For binary data:

Binary 1 → Higher carrier frequency (f1)
Binary 0 → Lower carrier frequency (f0)

For example:

Input:       1 0 1 1 0

FSK Signal:  f1 f0 f1 f1 f0


The receiver analyzes the frequency of each bit interval and determines whether the received bit is 0 or 1.

Technologies Used
HTML5
CSS3
JavaScript
HTML Canvas API
Project Structure
FSK-Simulator/
├── README.md
├── src/
│   └── fsk_simulator.html
├── testbench/
│   └── fsk_testbench.html
└── output/
    └── simulation_output.html

How to Run
Download or clone this repository.
Open src/fsk_simulator.html in a web browser.
Enter a binary sequence such as:
10110010

Set the frequencies for binary 0 and 1.
Click Simulate FSK.
Observe the generated waveform and demodulated output.
Example
Input Data       : 10110010
Frequency for 0  : 5 Hz
Frequency for 1  : 10 Hz
Recovered Data   : 10110010
Status           : PASS

Applications of FSK

FSK modulation is used in several digital communication systems, including:

Data modems
Radio communication
Caller ID systems
Telemetry
Wireless communication
Digital signaling
Objective

The main objective of this project is to provide an interactive

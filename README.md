🔐 AES Encryption Engine – VLSI Implementation
📌 Project Overview

This project implements an AES (Advanced Encryption Standard) Encryption Engine using Verilog HDL and Cadence VLSI tools. AES is a widely used symmetric encryption algorithm that ensures confidentiality and security in digital data transfer. The engine is capable of performing 128-bit key encryption, making it suitable for hardware security applications.

⚡ Features

Implements AES-128 encryption algorithm

Core modules:

SubBytes (Byte substitution using S-box)

ShiftRows (Cyclic row shifting)

MixColumns (Column mixing transformation)

AddRoundKey (Key addition with state matrix)

Key Expansion (Round key generation)

Handles 128-bit plain text & key input

Produces 128-bit encrypted output

Designed in modular Verilog RTL for clarity and scalability

🛠 Tools & Technologies

Verilog HDL – RTL design

Cadence NC-Sim / SimVision – Simulation & functional verification

Cadence Genus – RTL Synthesis & Timing Analysis

Cadence Innovus – Place & Route (Physical design)

GDSII Export – Final chip layout generation

✅ Results

Successfully implemented and verified AES-128 encryption engine

Testbenches validate encryption across multiple plaintexts and keys

Synthesized netlist with optimized area, power, and timing reports

Physical design completed with layout (GDSII) generation

🚀 Applications

Data encryption in IoT and embedded devices

Secure communication in hardware systems

Cryptography-based VLSI design research

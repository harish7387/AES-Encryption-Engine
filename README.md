🔐 AES Encryption Engine – VLSI Implementation
📌 Project Overview

This project implements an AES (Advanced Encryption Standard) Encryption Engine using Verilog HDL and Cadence VLSI tools. AES is a widely used symmetric encryption algorithm that ensures confidentiality and security in digital data transfer. The engine is capable of performing 128-bit key encryption, making it suitable for hardware security applications.

⚡ Features

1.Implements AES-128 encryption algorithm

2.Core modules:

  a.SubBytes (Byte substitution using S-box)

  b.ShiftRows (Cyclic row shifting)

  c.MixColumns (Column mixing transformation)

  d.AddRoundKey (Key addition with state matrix)

  e.Key Expansion (Round key generation)

3.Handles 128-bit plain text & key input

4.Produces 128-bit encrypted output

5.Designed in modular Verilog RTL for clarity and scalability

🛠 Tools & Technologies

1.Verilog HDL – RTL design

2.Cadence NC-Sim / SimVision – Simulation & functional verification

3.Cadence Genus – RTL Synthesis & Timing Analysis

4.Cadence Innovus – Place & Route (Physical design)

5.GDSII Export – Final chip layout generation

✅ Results

1.Successfully implemented and verified AES-128 encryption engine

2.Testbenches validate encryption across multiple plaintexts and keys

3.Synthesized netlist with optimized area, power, and timing reports

4.Physical design completed with layout (GDSII) generation

🚀 Applications

1.Data encryption in IoT and embedded devices

2.Secure communication in hardware systems

3.Cryptography-based VLSI design research

# 4-bit Adder in Verilog

## What this is
A 4-bit adder that takes two 4-bit numbers and outputs their sum.
Built and simulated on Ubuntu using Icarus Verilog and GTKWave.

## Tools used
- Icarus Verilog 12.0
- GTKWave 3.3.126
- Ubuntu 22.04

## How to simulate
iverilog -o adder_sim adder.v adder_tb.v
vvp adder_sim
gtkwave wave.vcd

## What I learned
- Verilog module structure
- Testbench writing
- Simulation and waveform viewing on Linux

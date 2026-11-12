
# AuthentiRx - Repetition Code Decoder

## Overview
This project implements a repetition-code fuzzy extractor using SystemVerilog.

## Files
- design.sv - RTL implementation of the repetition decoder.
- testbench.sv - Self-checking testbench for functional verification.

## Parameters
- REP = 5 (default repetition factor)
- KEY_BITS = 64

## Verification
The testbench includes:
1. Correctable noise testing.
2. Over-noisy group testing.
3. Clear operation testing.
4. Back-to-back key decoding.
5. Wipe operation testing.
6. Monte Carlo key recovery analysis.

## Simulation
The design and testbench can be simulated using EDA Playground with a SystemVerilog-compatible simulator.

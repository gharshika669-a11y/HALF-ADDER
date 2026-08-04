# Half Adder using Verilog

## Overview

A Half Adder is a combinational circuit that adds two single-bit binary numbers. It produces two outputs:

- Sum
- Carry

## Boolean Expressions

Sum = A XOR B

Carry = A AND B

## Truth Table

| A | B | Sum | Carry |
|---|---|-----|-------|
|0|0|0|0|
|0|1|1|0|
|1|0|1|0|
|1|1|0|1|

## Files

- half_adder.v - Verilog design
- half_adder_tb.v - Testbench
- simulation.png - Simulation waveform
- README.md - Project documentation

## Software Used

- Icarus Verilog
- GTKWave

## How to Run

Compile:

```bash
iverilog -o half_adder half_adder.v half_adder_tb.v
```

Run:

```bash
vvp half_adder
```

Generate waveform:

```bash
gtkwave dump.vcd
```

## Output

The simulation verifies all four possible input combinations and matches the Half Adder truth table.

## Author

Your Name
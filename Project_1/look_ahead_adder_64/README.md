# 2-Bit Look Ahead Adder (64-bit)

## Objective

This adder model was implemented using a structural gate-level implementation of a 2-bit look ahead adder combined together into a look ahead adder, which unlike the ripple adder version, allow for quicker computation, as each internal modular look ahead module is parallel in nature (although the overall structure is sequential).

Each modular circuit is capable of taking 4 bits and summing them into a two bit output.

This module tested: all possible combinations from 0 to 31 and, separately, two large 32-bit integers.

## Waveforms

Test 1: Simulation results from the Verilog representation of this 2-Bit Look Ahead Adder **(All possible combinations from 0 to 31)**

![Project_1 Waveform for Test 1](https://github.com/Megha052002/Projects/blob/2990c479b7f1b39a9c2aced375fdd76f10c7571b/Project_1/look_ahead_adder_64/Simulation%20Waveforms/project1_test_C.png)

Test 2: Simulation results from the Verilog representation of this 2-Bit Look Ahead Adder **(Two large 32-bit integers)**

![Project_1 Waveform for Test 2](https://github.com/Megha052002/Projects/blob/2990c479b7f1b39a9c2aced375fdd76f10c7571b/Project_1/look_ahead_adder_64/Simulation%20Waveforms/project1_test_D.png)

## Source Files

- **2-Bit Look Ahead Adder Module** - look_ahead_adder_64.v

- **2-Bit Look Ahead Adder Test Bench** - look_ahead_adder_test.v

# MIPS_single_cycle_Microprocessor
32-bit MIPS general purpose integer microprocessor & config it on FPGA
Phases:
1-Block diagram:
In this project, we are aiming to implement a 32-bit single-cycle microarchitecture MIPS processor based on Harvard Architecture. The single-cycle microarchitecture executes an entire instruction in one cycle. In other words instruction fetch, instruction decode, execute, write back, and program counter update occurs within a single clock cycle.

Referring to figure, you are required to write the RTL Verilog files for all submodules of the MIPS processor (e.g. Register File, Instruction Memory, etc.). Then, implementing the top module of the MIPS processor. Finally, you will configure this processor on Cyclone® IV FPGA device.

Capture

2- Write RTL modules in Verilog and instantiate in TOP
Capture PNG2

3- Simulate the TOP in Modelsim with 3 different programs: Factorial program, GCD of two numbers program and Fibonacci sequence program
program1: GCD of (180, 120)
program1 (2)

program2: Factorial of "7"
program2 (2)

program3: Fibonacci sequence program
program3 (2)
4- Configurated it on Cyclone IV FPGA Kit using Intel® QUARTIS PRIME
syn
Resources :David M. Harris, Sarah L. Harris - Digital Design and Computer Architecture

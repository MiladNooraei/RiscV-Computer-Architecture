
# RiscV Semulation

I Used verilog to implement RiscV Architecture
![RiscV_Data_Path](https://github.com/MiladNooraei/RiscV-Computer-Architecture/assets/108691050/d5547133-3694-4af8-bc2e-bc542b1085cf)

## Description

This project has following modules : 
- Multiplexer2To1
- Mem_WB(Write Back)_Resgister
- dataMemory
- EX_Mem_Register
- AdderModule32bit
- ALU
- Multiplexer2To1_5bit
- ID(Instruction Decode)_EX(Execute)_Register
- RegisterFile
- ALUControlUnit
- ControlUnit
- SignExtendModule
- IF(Instruction Fetch)_ID(Instruction Decode)_Register
- fetchState

Where fetchState also contains :

    1. Multiplexer2To1
    2. PC(Program Counter)
    3. instructionCache
    4. instructionMem

And all these modules are wired together in "RiscV.v" file.
There is also a text file named "input.txt" which contains input data.

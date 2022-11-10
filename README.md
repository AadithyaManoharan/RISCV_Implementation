
                   RISCV Implementation

Team Members:
Aadithya manoharan MT21182
N Kartheek Ram Reddy MT21198


**** Modules used:****

1. Fetch.v             -> Instruction Fetch stage.
2. IF_ID_Register.v    -> register between the Instruction_Fetch and Decode stage.
3. Register.v          -> It contains all the registers used.
4. Decode.v            -> Decode stage.
5. ID_EX_Register.v    -> register between the Decode and execute stage.
6. Execute.v           -> Execute stage.
7. EX_M_Register.v     -> register between the execute and memory stage.
8. Memory.v            -> Memory Access stage.
9. M_WB_Register.v     -> register between the Memory and Writeback.
10. Writeback.v        -> Writeback stage.


The testbench that needs to be used is:
1. Fetch_tb   -> This testbench includes all the modules mentioned above


**Testing Environment:**

Download the zipfile and open project1.xpr

Binaries Used:
1. instr_Mem.txt    -> to store the required instructions in binary form
2. Reg_mem.txt      -> contains the initial values of registers  
3. Memory.txt       -> contains initial memory values
4. MMR.txt          -> contains memory mapped register values  

The updated register values will be printed on the console window & observe the simulation waveform to see the pipeline flow.


# MIPS_CPU

This is a CPU with MIPS I Instruction Set Architecture. This is just a functional CPU, hence it should perform all MIPS I instructions without errors, but it is not pipelined. Hence this CPU is accurate although it loses out on efficiency. 

This CPU uses a single Avalon compatible memory-mapped interface to interact with memory. The CPU acts as a bus controller, and issues read and write transactions in order to change memory contents.

Brief introduction of each folder:
- docs: Has our MIPS CPU datasheet. Shows our implementation and testing.
- rtl: The actual CPU itself. It is written using verilog.
- test: Tests in assembly that we created to test the functionality of the CPU. Look at the readme.txt under the test folder to run the tests on the CPU.


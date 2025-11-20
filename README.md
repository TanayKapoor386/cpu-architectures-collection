# cpu-architectures-collection

Multiple CPU Designs & Architectures built from scratch.

# Docker Container Specs
Linux

# 5-Stage Pipelined CPU
Instruction Fetch (IF) -> Instruction Decode/Register Read (ID/RR) -> Execute (EX) -> Memory Access (MEM) -> Write Back (WB)

1. The Worst Case Hardware is hand-drawn and outlined based on the Instruction Set Architecture (ISA). The final design choice uses an upper bound on the hardware requirements, sacrificing space complexity for processor safety/efficiency. The hardware specs can be found here: [URL].
2. Each stage is implemented separately.
3. Instruction Fetch (IF) and Memory Access (MEM) each have their own Random Access Memory (RAM).
4. Assembly/Machine Code can be manually loaded into the Read Only Memory (ROM) and executed according to the ISA.

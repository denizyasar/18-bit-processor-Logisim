# 18-bit Processor (Logisim)

In this project, an 18bit architecture processor will be designed and implemented in Logisim which will support instruction set; AND, OR, ADD, LD, ST, ANDI, ORI, ADDI, XOR, XORI, JUMP, BEQ, BGT, BLT, BGE, BLE. The data bus and address sizes will be 18-bits.

There will be 16 operations designed and implemented in this architecture. Therefore, we decided to allocate 4 bits for opcode. To have a more readable design and simplify the implementation, we decided to use last 4 bits for operation. Rest of the opcode is divided for source and destination registers, immediate value, and addresses. Again, we will allocate 4 bits for register addressing as we will implement 16 registers. First bits of code are reserved for immediate value, jump, branch, and LD/ST addresses. For ADD, AND, OR, and XOR operations, after using necessary bits for registers, the first 2 bits left unused.

![ISA](https://user-images.githubusercontent.com/65470564/152025187-01644de8-8e3b-4ed0-924b-8c451d2791c2.jpg)

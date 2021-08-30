# x86 Buffer Overflow and Exploit Development Notes


## x86 Architecture Registers
EAX, AX, AH, AL - accumulator register - arithmetic results, output of function call, etc.
EBX, BX, BH, BL - base register - base pointer for memory access
ECX, CX, CH, CL - counter register - loop counter and for arithmetic shifts
EDX, DX, DH, DK - data register - stores extended results of an arithmetic instruction
ESI, SI         - source index register - stores source address when performing copy or comparison operations
EDI, DI         - destination index register - stores destination address when performing copy or comparison operations
EIP             - instruction pointer - points to the current instruction being executed

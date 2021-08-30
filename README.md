# Buffer Overflows and Exploit Development
<br>

## x86 Architecture Registers
<br>
EAX, AX, AH, AL - accumulator register - arithmetic results, output of function call, etc.<br>
EBX, BX, BH, BL - base register - base pointer for memory access<br>
ECX, CX, CH, CL - counter register - loop counter and for arithmetic shifts<br>
EDX, DX, DH, DK - data register - stores extended results of an arithmetic instruction<br>
ESI, SI         - source index register - stores source address when performing copy or comparison operations<br>
EDI, DI         - destination index register - stores destination address when performing copy or comparison operations<br>
EIP             - instruction pointer - points to the current instruction being executed<br>

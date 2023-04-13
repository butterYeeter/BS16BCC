# BS16BCC
butterYeeter's Simple 16 Bit Crappy CPU(BS16BCC)

This is a repo containing the logisim evo .circ files for my crappy cpu project :D

I have plans to make this turing complete and eventually build this on bread boards. I also plan on writing a basic assembler in C for this CPU.

![image](https://user-images.githubusercontent.com/100842250/231858384-9efd1a2a-4878-442f-9996-3a6377190cdc.png)

Goals:
- **ISA TO BE REDESIGNED**
- Make a turing complete 16 bit CPU with these instructions:
    - ADD - adds A and B registers
    - MUL - multiplies value of A with value of B
    - DIV - divides A by B
    - SUB - subtracts B from A
    - JMP - sets the values of the counter unconditionally
    - CMP - compares A and B. This instruction takes the type of comparison as input e.g. >, =, <
    - JMC - sets the value in the counter to the the specified parameter if CMP returns true
    - JM0 - sets the value of the counter to the specified parameter if A = 0
    - LDA - load immediate into A
    - LAA - load value of ALU into A
    - LDB - load immediate into B
    - LAB - load value of ALU into B
    - LDC - load immediate into C
    - LAC - load value of ALU into C
    - LDT - load immedaite into Temp
    - LAT - load value of ALU into Temp
    - RDA - load the value of A onto the bus
    - RDB - load the value of B onto the bus
    - RDC - load the value of C onto the bus
    - RDT - load the value of Temp onto the bus
    
- Write a complete assembler in C complete with ints, floats chars and bools.Should also have\
  flow control like for loops and if statements.
  
- Write pong in assembler language
  
- Implement the logical circuitry on breadboards to mess around with.
  
- Future upgrades:
    - Add RAM storage
    - 32 Bit
    - 2's Complement representation of numbers
    - Floating Point Unit
    - Implement stack, call stack and multiple program loading in RAM.
  
  
- Current tasks:
    - Complete 8 bit prototype with simple instructions. #DISCARDED
    - Hardware addition, multiplication, division and subtraction for unsigned ints. #COMPLETE
    - Configure instuction decoder. #TODO
    - Review ISA and improve it. #TODO
    - Add RAM for temp storage. #TODO
    - Screen output? #TODO
    
    

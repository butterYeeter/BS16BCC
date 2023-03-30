# BS16BCC
butterYeeter's Simple 16 Bit Crappy CPU(BS16BCC)

This is a repo containing the logisim evo .circ files for my crappy cpu project :D

I have plans to make this turing complete and eventually build this on bread boards. I also plan on writing a basic assembler in C for this CPU.

Goals:\
\tMake a turing complete 16 bit CPU with these instructions:\
\t\tADD - adds A and B registers\
\t\tMUL - multiplies value of A with value of B\
\t\tDIV - divides A by B\
\t\tSUB - subtracts B from A\
\t\tJMP - sets the values of the counter unconditionally\
\t\tCMP - compares A and B. This instruction takes the type of comparison as input e.g. >, =, <\
\t\tJMC - sets the value in the counter to the the specified parameter if CMP returns true\
\t\tJM0 - sets the value of the counter to the specified parameter if A = 0\
\t\tLDA - load immediate into A\
\t\tLAA - load value of ALU into A\
\t\tLDB - load immediate into B\
\t\tLAB - load value of ALU into B\
\t\tLDC - load immediate into C\
\t\tLAC - load value of ALU into C\
\t\tLDT - load immedaite into Temp\
\t\tLAT - load value of ALU into Temp\
\t\tRDA - load the value of A onto the bus\
\t\tRDB - load the value of B onto the bus\
\t\tRDC - load the value of C onto the bus\
\t\tRDT - load the value of Temp onto the bus
    
\tWrite a complete assembler in C complete with ints, floats chars and bools.Should also have\
\tflow control like for loops and if statements.
  
\tWrite pong in assembler language
  
\tImplement the logical circuitry on breadboards to mess around with.
  
\tFuture upgrades:\
\t\tImplement stack, call stack and multiple program loading in RAM.
  
  
\tCurrent tasks:\
\t\tComplete 8 bit prototype with simple instructions.\
\t\tHardware addition, multiplication, division and subtraction for floats and ints.\
\t\tReview ISA and improve it.\
\t\tScreen output?
    
    

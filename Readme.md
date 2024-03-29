# Computer-System-Architecture

---  

## Index  
[_View source code of this repository on GitGub_](https://github.com/ravi-prakash1907/Computer-System-Architecture/)  

>
> 1. [Sample Machines](https://github.com/ravi-prakash1907/Computer-System-Architecture/tree/master/Machines)  
>   - For [Diret Instruction-Set](https://github.com/ravi-prakash1907/Computer-System-Architecture/tree/master/Machines/2061_Direct_Ravi)  
>   - For [Indiret Instruction-Set](https://github.com/ravi-prakash1907/Computer-System-Architecture/tree/master/Machines/2061_Indirect_Ravi)  
> 2. [Solutions to the Practicle Programs](https://github.com/ravi-prakash1907/Computer-System-Architecture/tree/master/Operations%20for%20Programs)  
> 3. [Download _CPUSim 3.6.9_](https://github.com/ravi-prakash1907/Computer-System-Architecture/raw/master/CPUSim3.6.9%20Downloadable.tar.gz)  
> 4. [CPUSim Official](https://www.cs.colby.edu/djskrien/CPUSim/)  
> 

---  

## Practical List  
![P1](./Practical%20List/p1.png)
![P2](./Practical%20List/p2.png)


## The Header:
  { **[OP-Code] [---ADDR---]** }

  OP-Code: It's operation code of the instruction which is of 4-bits usually
  ADDR: It's the address field where the actual data is stored & has a size of 12-bits


## Registers in CPU:
```

1. AC  
   Accumulator Counter  
   16-bits  
   Mainly used for final computation  

2. PC  
   Program Counter  
   12-bits  
   Used to store of next step i.e. to be executed  

3. IR  
   Information Register  
   16-bits  
   Keeps **entire** data instructions  

4. DR  
   Data Register  
   16-bits  
   It stores actual data (_eg. y = 10_)  

5. AR  
   Address Register  
   12-bits  
   The address is stored here  

6. I  
   Index  
   1-bit  
   Stores the **index** of value/data  

7. S  
   Switch i.e. flip-flop  
   1-bit  
   Stores instruction about Start/Stop flip-flop  

8. E  
   Extra  
   1-bit  
   It stores the carry-bit (_eg. while adding 1+1, E will store '1'_)  

```  

---  

## Instruction cycle for the execution of any program:

a. **Fetch**:
    _An instruction if fetched from the memory_

b. **Decode**:
    _Decodes the fetched instruction_

c. **Read**:
    _The effective i.e. actual address is extracted from the memory_  
    _It's an instruction that has an Indirect address_  

d. **Execution**:
    _Finally the fetched instruction is executed_



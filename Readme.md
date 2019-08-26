This directory Holds the paracticals and information as per the Computer System Architecture (CSA) as in the B.Sc. (H) Computer Science

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

<hr />

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

<hr />

##### A directly downloadable zipped file is also given which is exactly same as that you need to create in the Practical classes. So you can simpally extract it and use it as a helping module.
##### The complete set-up is also provided in the same.

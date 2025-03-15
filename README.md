#DAY1 and DAY2

Different applications are run on hardware core, through the process of converting and compiling the data into assembly language which is then fed to the core
![day1](https://github.com/user-attachments/assets/a14a0817-b010-448a-991d-a14e118dd531)



LAB 


Creating a simple C code for finding sum of N numbers
![Screenshot 2025-03-11 171101](https://github.com/user-attachments/assets/6a169063-fd8a-4221-a110-1e714750406b)

Executing the C code using RISCV64 

![Screenshot 2025-03-11 174507](https://github.com/user-attachments/assets/e43af1a2-659e-4e02-ac4b-ba34db65bb2d)
![Screenshot 2025-03-11 174428](https://github.com/user-attachments/assets/919f1aed-0b34-4776-878f-635cb5fe14df)
use ':reg' to find the contents of the register and just press enter to run the next command/instruction
![Screenshot 2025-03-11 180502](https://github.com/user-attachments/assets/dd49792b-3763-4f58-8789-2a52487cf290)



Base Instructions 
8 bit = 1 byte
4 bytes = word
8 bytes = doubleword
1 doubleword = 64 bits

Note: For positive numbers the MSB value will be 0 

  For negative numbers the MSB value will be 1
![base int instructions](https://github.com/user-attachments/assets/66aca04b-69d0-437f-9023-982f07fa5648)

![Screenshot 2025-03-09 215003](https://github.com/user-attachments/assets/0f0681e6-1105-4e8b-b228-d5c5cdbb9921)

![Screenshot 2025-03-09 220329](https://github.com/user-attachments/assets/2f8b5338-d16c-46b8-8969-0aad61caac53)



Risc-V belongs to little endian system where LSB is placed in the right extreme and MSB to the left extreme 

![Screenshot 2025-03-10 222431](https://github.com/user-attachments/assets/5d23b13e-4dc3-43ed-9313-b219162292eb)

![Screenshot 2025-03-10 224741](https://github.com/user-attachments/assets/8773aa02-051d-4688-8d4e-a75696aada67)


LAB

Create a C code for finding unsigned Highest value and execute using RISCV

![Screenshot 2025-03-11 182622](https://github.com/user-attachments/assets/a94d94ed-7565-40e4-a671-9debe033e2ac)
![Screenshot 2025-03-11 182701](https://github.com/user-attachments/assets/1205dba7-a5c6-4bc7-adb8-2c0c071170e5)
![Screenshot 2025-03-11 183518](https://github.com/user-attachments/assets/0f5d3e34-76c6-446e-b092-abed078ee4c3)
![Screenshot 2025-03-11 183914](https://github.com/user-attachments/assets/243908cb-affe-4343-b37e-5b340d54ac2c)


LAB to rewrite C program using ASM language 


![Screenshot 2025-03-12 083527](https://github.com/user-attachments/assets/9fd36c4e-5e28-42a4-975d-af9cc78ecadd)

![Screenshot 2025-03-12 091815](https://github.com/user-attachments/assets/d08f009b-c513-4743-8191-cf1271ccb2b8)

![Screenshot 2025-03-12 091715](https://github.com/user-attachments/assets/92cc986f-1196-430f-a6c2-ab74f0f85523)


![Screenshot 2025-03-12 092500](https://github.com/user-attachments/assets/0bd50a80-ec1c-44d7-bc01-13a20ada040f)

![Screenshot 2025-03-12 094415](https://github.com/user-attachments/assets/9a2d4016-27ed-4d87-a296-35adf0d62465)

![Screenshot 2025-03-12 094544](https://github.com/user-attachments/assets/5c89567d-18b2-446a-aa0b-f05e5e96ed9e)

![Screenshot 2025-03-12 094900](https://github.com/user-attachments/assets/e7b3e54f-94f3-4a3b-b04a-7cf41b7cfac2)

![Screenshot 2025-03-12 094956](https://github.com/user-attachments/assets/217ac80f-b033-48e5-9437-5aa6e7fbd8a5)

![Screenshot 2025-03-12 095212](https://github.com/user-attachments/assets/de4ffe78-de5c-4b56-80e3-927a300a48a7)



DAY-3



Get started with Makerchip and explore the various examples and tutorials 

![Makerchip lab steps](https://github.com/user-attachments/assets/f231be70-e509-4db4-b539-190af5cf3579)


![makerchip1](https://github.com/user-attachments/assets/a06adf46-51ae-4d98-ae8f-9dbb15f6fa90)


![makerchip2](https://github.com/user-attachments/assets/ec907145-bb74-43d7-9640-945ff7d4c0c3)

Addition
![in1+in2](https://github.com/user-attachments/assets/bc807e73-9e7c-47de-b229-af121bb85106)

Using && 
![Screenshot 2025-03-08 200858](https://github.com/user-attachments/assets/5d6ba0bc-a8a5-4e5b-b4d2-5fbd62b884a6)

Implementation of inverter 
![inverter](https://github.com/user-attachments/assets/8949ee5a-a4fe-4d4e-acbd-02a80ace8763)

Implementation of MUX
![mux](https://github.com/user-attachments/assets/602b8db6-2dd7-4cf9-ad1d-349a231966f5)

Implementation of MUX using vectors 
![muxvector](https://github.com/user-attachments/assets/7d5a841a-957a-4c5a-803d-b3721a37f925)


Calculator 

![image](https://github.com/user-attachments/assets/3ef97353-dd1b-4527-a97c-116931d12ed7)



Pythagoras Theorem 
![pipeline-pythagoras](https://github.com/user-attachments/assets/cfc69d85-6d30-4211-a406-5eb9bd507f32)

DAY-4

This is the architecture of RISC-V CPU.
The program counter is our pointer , which is connected to the instruction memory that holds the instruction that has to be executed. Next the instruction must be decoded which is done by the decoder.
We have two source registers RFRd (Register File Read) and ALU is the calculator/ any logical unit that we have designed.We have Dmem (memory) that stores or loads the data.




![Screenshot 2025-03-15 175652](https://github.com/user-attachments/assets/f33c8518-8e81-49eb-832c-54d2297f877b)





During the fetch stage, processors fetches the instruction from the memory to the address pointed by the program counter. The program counters holds the address of the next stage, which is after 4 cycles and the instruction memory holds the set of instruction to be executed.

![image](https://github.com/user-attachments/assets/7b24f4f1-4242-43c2-99b9-84275b802ddb)
![image](https://github.com/user-attachments/assets/48a328de-c82c-4db0-beff-5f0632616f34)





There are SIX instruction types in RISC-V architecture :
* Register type (R)
* Immediate type (I)
* Store type (S)
* Branch type (B)
* Upper immediate type (U)
* Jump type (J)


![image](https://github.com/user-attachments/assets/df75e986-42d0-455d-ba14-d1a15e41713d)


For Immediate type
![image](https://github.com/user-attachments/assets/9d04c8b8-25b4-4ab9-b049-7156e3d2fadd)


For other types
![image](https://github.com/user-attachments/assets/51b25f95-3000-4ee3-88ed-f660b80db33f)


Using WHEN condition (applicable for only R-type, S-type and B-type
![image](https://github.com/user-attachments/assets/ea2dd249-558b-40a4-8010-40fa7debd901)


Now we need to decode the instructions 
* RV32I base instruction set
NOTE: "`BOGUS_USE" is used to avoid warings in log which are created when other signals that are present are not used (it is a system verilog macro) 
![image](https://github.com/user-attachments/assets/9de092ea-b0b1-4927-90d0-8d05f52ea0d5)



REGISTER FILE READ

![image](https://github.com/user-attachments/assets/c6a9dbd5-9174-446e-b6ab-ef9c50f1bef8)
![image](https://github.com/user-attachments/assets/a7a2fc3c-aa53-4c90-b5a3-1257a0c030bf)

The signals (outputs) coming out of the register files are given as inputs to the Arithmetic Logic Unit(ALU)
![image](https://github.com/user-attachments/assets/2b87f159-4681-42c6-8eb3-d0f2489ddc98)


ALU

![image](https://github.com/user-attachments/assets/70fd09df-da80-491b-9d67-da78d570d37c)


REGISTER FILE WRITE 

![image](https://github.com/user-attachments/assets/c405b776-923e-41fe-a9ed-13a8866e76b4)

![image](https://github.com/user-attachments/assets/24721461-ec4f-4afd-bc00-e33ac529171b)


ARRAYS

![image](https://github.com/user-attachments/assets/8269662f-04c3-43d3-947c-56cdff820653)

PIPELINED LOGIC OF ARRAYS

* RF Wr updates the values which is given as the input to RF Rd
![image](https://github.com/user-attachments/assets/fb4dca18-74f5-4e2d-b891-c9d4f529788d)


BRANCHES

RISC-V uses Conditional branches i.e a particular branch is taken when the condition is met

![image](https://github.com/user-attachments/assets/7a64bb03-c5ac-48f0-88da-2c46f49654be)
![image](https://github.com/user-attachments/assets/82d13b6a-cff8-4954-9b18-b9dc4a2a472e)


TESTBENCH

![image](https://github.com/user-attachments/assets/fdc2bf84-2e4e-4736-9506-f49e620015c6)



DAY-5

PIPELINING :


Pipelining of the CPU core allows easy retiming and reduces functional bugs. Pipelining allows faster computaion.In TL verilog the advantage is defining pipelines in systematic order is not necessary. 

![image](https://github.com/user-attachments/assets/9fb814e0-9fc6-48c9-92b1-01de59627f6b)


Waterfall Logic 
![image](https://github.com/user-attachments/assets/95696702-fd87-4a9a-a8fc-84b27e3aed8c)



Disadvantage of Waterfall Logic

Hazards - The problems with the timeing i.e the branch control comes at @3 and it has to be connected to the pc which is 2 cycles earlier . And the read operation can be performed only after the write operation.
![image](https://github.com/user-attachments/assets/0b43371a-45f2-4139-a645-1fdfa73a8592)
![image](https://github.com/user-attachments/assets/3d46d910-4730-4167-a726-e68c3c069ad1)
![image](https://github.com/user-attachments/assets/07fa8b1f-5694-4752-9f9a-813409a15331)

![image](https://github.com/user-attachments/assets/d3fd8ae0-45f7-4262-a606-c0635d168a18)
![image](https://github.com/user-attachments/assets/3de0cbde-43bc-41e1-88da-381d351d516f)


Partition Logic
![image](https://github.com/user-attachments/assets/117e254b-c2ef-4062-816b-41a23a9b00e9)

REGISTER FILE BYPASS used to Address Read-After-Write Hazard
![image](https://github.com/user-attachments/assets/0fa65b4b-028a-433e-a560-bf12bfaacb7c)
![image](https://github.com/user-attachments/assets/1ab70274-f90f-4acb-8aa6-a95beeb54dcb)

BRANCHES

These two cycles cannot be avoided 
![image](https://github.com/user-attachments/assets/602f13fa-3e9a-4c1d-a396-601b4e3346a3)
![image](https://github.com/user-attachments/assets/f32f9b71-774f-43f2-9918-40d2a47e5850)

Logic for Branch behaviour 
![image](https://github.com/user-attachments/assets/00bef646-e804-48d1-bc3a-d2779a6c3023)


LOAD and STORE

The load and store option is also included in RISCV for which a one read or write data memory is added. Similar to branch instruction the load also has a 3 cycle delay.
![image](https://github.com/user-attachments/assets/3a253e23-6f55-4d36-8c4f-a77061a9b683)
![image](https://github.com/user-attachments/assets/3cdbb7db-f9ad-4751-85ae-ef77d0f60cba)



WATERFALL DIAG FOR LOAD AND STORE

![image](https://github.com/user-attachments/assets/49652b89-11e0-4fd6-a224-9f001f89c734)

REDIRECT LOADS
![image](https://github.com/user-attachments/assets/b5c58842-dcc7-471c-a593-fd6bf1819c6a)


LOAD DATA
![image](https://github.com/user-attachments/assets/114996ad-a42f-496a-ad99-9d882d20a18b)
![image](https://github.com/user-attachments/assets/4554c8dc-7543-4dd5-9f9a-b6315b4d283c)



JUMPS- They are unconditional branches 
![image](https://github.com/user-attachments/assets/bcba259b-7b9f-4fa9-96ba-33d47818b32e)


Implementing Jumps
![image](https://github.com/user-attachments/assets/e29a0d88-7cb9-45c8-a4f7-36b77ec29436)













































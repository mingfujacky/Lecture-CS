---
marp: true
theme: default
class: default
size: 16:9
paginate: true
header: 國立陽明交通大學 電子與光子學士學位學程
headingDivider: 1
style: |
  section::after {
    content: attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total);
  }
  
  .small-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
  .small-grid img {
    width: 50%;
  }
  .middle-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
  .middle-grid img {
    width: 75%;
  }
  .grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 10px;
  }
  .grid img {
    width: 100%;
  }
  .red-text {
    color: red;
  }
  
  .blue-text {
    color: blue;  
  }

  .small-text {
    font-size: 0.50rem;
  }
---
# Computer Organization
- CPU
- Main memory
- Execution of the program
- Bus and interface
- Storage device

# von Neumann Model
![w:600 von Neumann Model](asset/image/ch00_von_neumann_model.png)

# CPU Basics
- Arithmetic/Logic Unit (ALU): perform operations (+, -, AND, XOR) on data
- Control Unit (CU): fetches instructions from memory, decodes them, and generates control signals to ALU, memory, and I/O devices
- Registers: temporary storage of information within the CPU
- Bus: transfer bit patterns (data, address, control) between CPU and main memory

![w:600](asset/image/ch02_cpu_bus_memory_0.png)

# Linkage Architecture between CPU and Memory
![w:600](asset/image/ch02_cpu_bus_memory_1.jpg)

# Central Processing Unit (CPU)
CPU is the brain of a computer, a chip with extremely complex circuits, which is used to execute program instructions stored in memory and control the processing and operation of digital data. It consists of
- Arithmetic Logic Unit (ALU)
- Control Unit (CU)
- Registers

# Arithmetic Logic Unit
- Perform mathematical operations such as addition, subtraction, multiplication and division
- Perform logical operations such as AND, OR, NOT and XOR (eXclusive OR)
![w:300](asset/image/ch02_logical_operations.png)

# Control Unit
- Control the flow of computer execution programs.
- Direct each system unit to carry out the tasks required.
- Coordinate the operation of the various system units.
- For example, it moves the program instructions that need to be executed from memory to the register, decodes the instructions, and then hands them over to the ALU for operation, and then puts the results back into register or memory

# Register
- CPU has a very small storage device, called a register, that can temporarily store instructions or data.
- Registers can be accessed faster than the main memory, which can greatly increase the performance of the CPU.
- Two types of register
  - General-purpose register
  - Special-purpose register
    - Instruction Register: hold the current instruction while the computer decodes and executes it
    - Program Counter: store the memory address of the next command the computer needs to run

# Bus
In the architecture of the linkage between CPU and memory, there are some transmission tools for transmitting electronic signals, called bus

| Bus | Purpose | Typical Direction |
|---|---|---|
| **Address Bus** | Specifies **where** to access | CPU → Memory |
| **Data Bus** | Transfers **what** is being read/written | CPU ↔ Memory |
| **Control Bus** | Specifies **what operation** to perform | Both directions |

CPU&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Memory
 │── Address: 1000 ───────►│
 │── Data: 42 ──────────►│
 │── Control: WRITE ───────►│

# Memory
- Memory is divided into various types based on speed, unit price, and attributes.
- Memory is used to store data and the results of calculations.
- In the von Neumann model, the memory stores both programs and data.
![w:600](asset/image/ch02_memory_types.png)

# Registers and Cache
- Registers: Built directly into the processor core. They offer the fastest speed and highest unit cost, but hold very little data.
- L1, L2, L3 Cache: Small, very fast memory close to the CPU. They store data the processor uses most often.



# Logisim Digital Logic Repository

This repository contains a comprehensive collection of digital logic circuit designs implemented in Logisim, organized by category. These circuits range from basic logic gates to more complex components like arithmetic circuits, flip-flops, registers, and counters.

## Repository Structure
├── Arithmetic Circuits
│ ├── Shift
│ │ ├── Bidirectional Shift Registers.circ
│ │ ├── Shift Left Register.circ
│ │ └── Shift Right Register.circ
│ ├── 4 Bit Binary Adder.circ
│ ├── Full Adder.circ
│ ├── Full Subtractor.circ
│ └── Half Adder.circ
├── Basic Logic Gates
│ ├── AND Logic gate.circ
│ ├── NOT Logic gate.circ
│ ├── OR Logic gate.circ
│ └── XOR Logic gate.circ
├── Counters
│ ├── 3 Bit Up Counter using JK FF.circ
│ ├── Asynchronous Counter.circ
│ └── Synchronous Counter.circ
├── Data Convertors
│ ├── Decoder.circ
│ └── Encoder.circ
├── Data Routing Circuits (Selector-Distributors)
│ ├── Demultiplexer.circ
│ └── Multiplexer.circ
├── Flip Flops
│ ├── D Flip Flop.circ
│ ├── JK Flip Flop.circ
│ ├── SR Flip Flop.circ
│ └── T Flip Flop.circ
├── Registers
│ ├── 4 Bit Register File.circ
│ ├── 4 Bit Register using D Flip Flop.circ
│ ├── 4 Bit Registor File.circ
│ └── 4 Bit Registor using D Flip Flop.circ
└── Universal Gates
├── NAND Logic gate.circ
└── NOR Logic gate.circ

## Circuit Categories

### Arithmetic Circuits
Digital circuits that perform arithmetic operations such as addition, subtraction, and shifting.

- **Half Adder**: Adds two single binary digits (A and B) producing Sum and Carry outputs
- **Full Adder**: Adds three binary digits (A, B, and Carry-in) producing Sum and Carry-out
- **4-Bit Binary Adder**: Adds two 4-bit binary numbers using cascaded full adders
- **Full Subtractor**: Performs subtraction of three binary digits (A, B, and Borrow-in)
- **Shift Circuits**:
  - **Shift Left Register**: Shifts data left by one bit on each clock cycle
  - **Shift Right Register**: Shifts data right by one bit on each clock cycle
  - **Bidirectional Shift Register**: Can shift data left or right based on control input

### Basic Logic Gates
Fundamental building blocks for digital electronics.

- **AND Gate**: Output is HIGH only when all inputs are HIGH (A·B)
- **OR Gate**: Output is HIGH when any input is HIGH (A+B)
- **NOT Gate**: Inverts the input (A')
- **XOR Gate**: Output is HIGH when inputs are different (A⊕B)

### Counters
Sequential circuits that cycle through a fixed sequence of states.

- **Synchronous Counter**: All flip-flops share the same clock signal
- **Asynchronous Counter**: Each flip-flop is clocked by the previous one (ripple counter)
- **3-Bit Up Counter using JK FF**: Counts from 000 to 111 using JK flip-flops

### Data Convertors
Circuits that transform data between different formats.

- **Encoder**: Converts 2ⁿ input lines to n output lines (e.g., 4-to-2 encoder)
- **Decoder**: Converts n input lines to 2ⁿ output lines (e.g., 2-to-4 decoder)

### Data Routing Circuits
Circuits that direct data flow between multiple paths.

- **Multiplexer (MUX)**: Selects one of many input lines to a single output line
- **Demultiplexer (DEMUX)**: Routes a single input to one of many output lines

### Flip Flops
Basic memory elements that store one bit of information.

- **SR Flip Flop**: Set-Reset flip-flop with two inputs (S and R)
- **JK Flip Flop**: Improved version of SR flip-flop with toggling capability
- **D Flip Flop**: Stores the D input value on clock edge
- **T Flip Flop**: Toggles output state when T input is high

### Registers
Collections of flip-flops that store multiple bits of data.

- **4 Bit Register File**: Contains multiple 4-bit registers with address selection
- **4 Bit Register using D Flip Flop**: Basic 4-bit storage using D flip-flops
- **4 Bit Registor File**: Alternative implementation of register file
- **4 Bit Registor using D Flip Flop**: Alternative implementation using D flip-flops

### Universal Gates
Logic gates that can implement any Boolean function.

- **NAND Gate**: Universal gate (NOT-AND), can implement all other gates
- **NOR Gate**: Universal gate (NOT-OR), can implement all other gates

## Getting Started

### Prerequisites
- [Logisim Classic](http://www.cburch.com/logisim/) or 
- [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution) (recommended)

### Opening Circuit Files
1. Install Logisim on your system
2. Clone this repository: `git clone <repository-url>`
3. Launch Logisim
4. Navigate to File > Open and select the desired .circ file


# SimpleCPU with ROM Memory Implementation with VHDL and Quartus

Welcome to the SimpleCPU with ROM Memory repository! This project extends the SimpleCPU design by incorporating a Read-Only Memory (ROM) to store instructions for the CPU. The SimpleCPU with ROM Memory is implemented using VHDL within the Quartus environment, providing a comprehensive solution for CPU architecture with instruction fetching capabilities from ROM.

## Overview

The SimpleCPU with ROM Memory builds upon the basic CPU architecture by integrating a ROM memory module to store program instructions. The ROM memory contains a predefined set of instructions that the CPU fetches and executes sequentially. This approach enables the CPU to execute programs stored in ROM without the need for external instruction loading or dynamic memory allocation.

## Features

### 1. CPU Core with ROM Interface

The SimpleCPU core is enhanced with a ROM memory interface to fetch instructions from the ROM module. The CPU core includes components for instruction fetching, decoding, and execution, allowing it to operate seamlessly with ROM-based instruction sets.

### 2. ROM Memory Module

The ROM memory module stores program instructions in a non-volatile memory array. Instructions are preloaded into the ROM during initialization or programming, and the CPU fetches them sequentially for execution. The ROM module may be implemented using static RAM (SRAM) or flash memory technologies, depending on the target platform requirements.

### 3. Instruction Set Architecture (ISA)

The CPU supports an instruction set architecture (ISA) defined by the instructions stored in the ROM memory. The ISA specifies the operation codes (opcodes) and operand formats used by the CPU to execute instructions fetched from ROM. The CPU core interprets and executes instructions based on the ISA definition.

### 4. Quartus Integration

The SimpleCPU with ROM Memory is designed and implemented using VHDL within the Quartus environment. Quartus provides tools for designing, simulating, synthesizing, and programming FPGA-based digital circuits, making it suitable for developing complex CPU architectures with ROM memory integration.

## Usage

To use the SimpleCPU with ROM Memory implemented with VHDL and Quartus, follow these steps:

1. Clone the repository to your local machine.

2. Set up the Quartus environment on your computer. Install the necessary software packages and configure the development environment according to the provided instructions.

3. Open the SimpleCPU with ROM Memory project in Quartus and review the VHDL source code files comprising the CPU and ROM memory modules. Understand the architecture, interfaces, and functionality of the components.

4. Compile the VHDL source code and perform functional simulations to verify the correctness of the CPU design and ROM memory integration. Use simulation tools provided by Quartus to observe CPU behavior, execute test programs, and debug potential issues.

5. Synthesize the CPU design with ROM memory integration to generate a hardware description file (e.g., .vhd or .v) suitable for implementation on FPGA or ASIC platforms. Follow the synthesis and implementation process outlined in the Quartus documentation.

6. Deploy the synthesized CPU design with ROM memory integration onto the target hardware platform (e.g., FPGA development board) for testing and evaluation. Verify the functionality of the CPU in a real-world environment and assess its performance with ROM-based instruction execution.

## Contributing

Contributions to this repository are welcome! If you have suggestions for improvements, optimizations, or new features, please feel free to open an issue or submit a pull request. Whether you're experienced in digital logic design, VHDL programming, or CPU architecture, your contributions are valuable to enhancing the SimpleCPU with ROM Memory project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


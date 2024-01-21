# Dual Port RAM Verilog Implementation

## Overview

This repository contains the Verilog implementation of a Dual Port RAM. Dual Port RAM allows simultaneous read and write operations on separate ports, providing flexibility for various applications. The code is provided along with testbenches to ensure proper functionality.

## Contents

- **src/**: This directory contains the Verilog source code for the Dual Port RAM module.
  - `DualportRAM_src.v`: Verilog module for the Dual Port RAM.
  
- **testbenches/**: This directory includes testbenches to verify the functionality of the Dual Port RAM.
  - `DualportRAM_tb.v`: Testbench for the Dual Port RAM module.

- **sim/**: Simulation outputs will be stored in this directory.

## Usage

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/dual-port-ram.git
    cd dual-port-ram
    ```

2. Open the project in your preferred Verilog development environment.

3. Simulate the design using the provided testbench:

    ```bash
    cd sim
    <simulation_command> DualportRAM_tb.v
    ```

   Replace `<simulation_command>` with the appropriate command for your simulation tool (e.g., `iverilog`, `ncsim`, `modelsim`, etc.).

4. Review simulation results to ensure proper functionality of the Dual Port RAM.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Thank you for using and contributing to the Dual Port RAM Verilog implementation!

Happy coding!

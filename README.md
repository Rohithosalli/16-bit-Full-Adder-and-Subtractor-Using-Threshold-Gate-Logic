# 16-bit-Full-Adder-and-Subtractor-Using-Threshold-Gate-Logic
This repository contains the design, implementation, and simulation of a 16-bit full adder and 16-bit full subtractor using threshold gate logic. Threshold gates, known for their simplicity and efficiency, offer an alternative to traditional Boolean logic gates, achieving optimization in terms of power consumption and area.

#### The project includes:
* Verilog code for 1-bit and 16-bit full adder and subtractor circuits.
* Detailed simulation testbenches to validate functionality.
* Performance analysis comparing delay, power, and resource usage with traditional designs.
* Synthesized results using Vivado software targeting the Artix-7 FPGA (xc7a200tsbv484-3).

## Key Features

* Threshold Gate Logic: Employs threshold-based decision-making for efficient arithmetic operations.
* 16-bit Arithmetic Units: Designs for addition and subtraction of 16-bit binary numbers.
* Optimized for FPGA: Synthesized for Artix-7 FPGA to leverage hardware efficiency.
* Simulation and Validation: Includes testbenches for thorough functional verification.
  
## File Structure

1) Verilog/
     * tfa_16.v              # 16-bit Full Adder
     * tfs_16.v              # 16-bit Full Subtractor
     * trashold_full.v       # 1-bit Threshold Full Adder
     * trashold_sfull.v      # 1-bit Threshold Full Subtractor
2) Testbenches/
     * tfa_16b_tb.v          # Testbench for 16-bit Full Adder
     * tfs_16b_tb.v          # Testbench for 16-bit Full Subtractor
3) Docs/REPORT: 
      * Architecture_Diagrams # Diagrams of the full adder and subtractor
      * Performance_Results   # Performance metrics comparison
4) LICENSE                   # Project License
5) README.md                 # Repository Overview


## Getting Started

1) Clone this repository:"git clone [https://github.com/Rohithosalli/16-bit-Full-Adder-and-Subtractor-Using-Threshold-Gate-Logic](https://github.com/Rohithosalli/16-bit-Full-Adder-and-Subtractor-Using-Threshold-Gate-Logic).git"
2) Open the Verilog files in your preferred simulator (ModelSim, Vivado, etc.).
3) Run the provided testbenches to validate the designs.
   
## Dependencies

* Verilog-compatible simulation tools (Vivado).
* FPGA board (Artix-7 xc7a200tsbv484-3) for synthesis and implementation.

### Results

#### The designs were validated and synthesized. The threshold gate logic provided:
* Reduced Power Consumption: 11.127 mW vs. 12.12 mW in traditional designs.
* Comparable Delay: 10.031 ns vs. 7.424 ns in traditional designs.
* Improved Area Efficiency: Utilized fewer logic elements.

### Future Work

* Optimize designs to reduce delay further.
* Explore implementations for other arithmetic units using threshold gate logic.

### Contributions
Contributions are welcome! Feel free to fork this repository, make your improvements, and submit a pull request.


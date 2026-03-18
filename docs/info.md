<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project uses the TinyTapeout chain to build a digital multipler circuit from verilog code. It takes Verilog files and runs them through a series of tests:
- DOCS - tests if documents are up to date
- FPGA - tests if the verilog is able to run on an FPGA
- GDS - tests if the verilog code is synthesizable
- TEST - checks code functionality using a test bench

## How to test

After testing in a simulator, compile and run in this GitHub repository by going to the Actions tab and checking to see that all tests have passed for the most recent commits. 

## External hardware

No external hardware is used, this is for a bespoke custom chip.

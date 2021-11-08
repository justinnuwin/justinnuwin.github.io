+++
title = "SpeQtral"
date = "2021-02-14"
daterange = "Feb 2021 - Aug 2021"
author = "Software Contractor Part-time" 
cover = ""
tags = ["fpga", "verilog", "systemverilog", "kernel-development", "pcb design"]
keywords = ["fpga", "xilinx", "tdc", "time-digital-converter", "linux", "kernel", "high-speed", "pcb"]
description = "Development high-speed FPGA interface for a TDC application."
showFullContent = false
+++

I designed and developed a configureable 4-channel DDR LVDS Serialized AXI FPGA interface in SystemVerilog (up to 250MHz) for time-digital-converter application on an Xilinx Zynq SoC. 
The TDC was interfaced to the FPGA SoM that I designed.
In addition to the FPGA interface, I also developed the kernel and user-space drivers for accessing/debugging the interface and TDC from the SoC Linux environment.
To leverage full speed data transfers of the FPGA interface I designed, a AXI to USB 3.0 SuperSpeed interface was designed to stream the serialized TDC datastream to a downstream computer.

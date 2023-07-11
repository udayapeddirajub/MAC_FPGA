# FPGA MAC Module

This repository contains an efficient Multiply and Accumulate (MAC) module designed for FPGA implementations. The MAC module is a fundamental building block in many digital signal processing (DSP) applications, including audio and video processing, communications systems, and machine learning algorithms.

The MAC module in this repository is specifically designed with Booth multipliers and carry-select adders, which can be obtained from the accompanying repositories listed below:

Booth Multipliers: A collection of high-performance Booth multipliers optimized for FPGA designs.

Carry-Select Adders: Implementations of carry-select adders for efficient arithmetic operations in FPGA designs.

Features
High Performance: The MAC module leverages Booth multipliers and carry-select adders to achieve high-speed computations. The use of these optimized components enhances the overall performance of the MAC module.

Configurability: The MAC module offers flexibility in terms of data width, input scaling, and output precision. It can be easily customized to meet specific application requirements.

Low Resource Footprint: The design focuses on minimizing resource usage while maintaining high performance. This allows for efficient utilization of FPGA resources, enabling integration with complex systems.

Synchronous and Pipelined: The MAC module operates in a synchronous manner, ensuring precise timing control and synchronization with other modules. Pipelining techniques are employed to maximize throughput and minimize latency.



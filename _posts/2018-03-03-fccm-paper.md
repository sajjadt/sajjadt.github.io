---
layout: default
title: "Paper on acceleration of OpenVX graphs on FPGAs is accepted into FCCM 2018"
tags: research publication
---

Computer vision processing is computationally expensive and several acceleration solutions have been proposed. Among them, FPGAs offer a promising direction. A vision application is typically written in C/C++ and is difficult to compile into an efficient FPGA  implementation. OpenVX is a set of basic, widely used vision kernels. Vision pipelines can be defined as graphs of such kernels, all in C++. Accelerator vendors may support OpenVX kernel implementations, as in nVidia's VisionWorks. This work presents a framework for synthesizing an OpenVX graph-level specification of a vision pipeline into an optimized FPGA implementation using Intel i++ compiler. Three vision pipelines are developed using the framework. Preliminary results show that their performance is higher than either a multi-core CPU or an OpenCL-based FPGA implementation. The proposed framework compiles entire sub-graphs into FPGA pipelines, which is the main reason for the  performance and resource usage improvement compared to the OpenCL implementation.

---
layout: page
title: Research
---


### My research interests
1. High performance computer vision
2. Web Technologies
3. Programming Languages
4. Architecture and Compilers

While at UCIrvine I have led three research projects:

#### FPGA Accelration of Vision Processing
Computer vision algorithms are computationally expensive and are difficult to implement efficiently. Field Programmable Gate Arrays (FPGA)s offer a promising direction to reduce the computation cost by exploiting hardware parallelism. However, vision algorithms are often difficult to translate to FPGA bitstream efficiently. OpenVX is an industry standard for graph-based representation of vision algorithms. It defines a set of widely used vision kernels and data structures that can be combined to form a Directed Acyclic Graph (DAG) that represents a vision algorithm. This paper proposes an automatic FPGA acceleration framework for computer vision algorithms based on OpenVX specification, called AFFIX. AFFIX receives a vision algorithm in the graph form and employs several high level and low level optimization methods to deliver an efficient FPGA implementation.
It provides a configurable framework that enables vision algorithm developers to quickly develop, verify and test FPGA implementations of vision algorithms. The effectiveness of the proposed framework is demonstrated vie development of multiple vision algorithms and their evaluation.  

Supported by Intel Corp.
Related publication:

```
S.  Taheri,  J.  Heo,  P.  Behnam,  A.  V.  Veidenbaum,  A.  Nicolau,  ”Acceleration Framework for FPGA Implementation of OpenVX Graph Pipelines”, IEEE FCCM’18. [3]
```

#### OpenCV.js

OpenCV.js brings years of OpenCV development in computer vision processing to the web with high efficiency. It provides a collection of carefully selected computer vision functions ranging from image processing, object detection, video analysis, features extraction, deep neural networks, etc. ![pum_cover]({{site.url}}/assets/pum_32_cover.png){:style="float: right;margin-right: 7px;margin-top: 7px;width: 300px;"}Thanks to JavaScript portability, for the first time, a large collection of vision functions can be used not only on web browsers but also on embedded devices (e.g. IOTs using Node.js) and Desktop application development (e.g. Electron framework. Combined with recent web technologies, it helps in realizing novel web applications and experiences such as emerging virtual and augmented reality more efficiently. 



In addition, we have developed expansive online resources to help developers and researchers learn more about OpenCV.js and computer vision in general that can be accessed at:


<!-- 
OpenCV.js documentation and tutorials
OpenCV.js demos
OpenCV.js can also be used in Node.js based environments. It is published on NPM. -->

Supported by Intel Corp.

Relatd publications:
```
1. S. Taheri, A. V. Veidenbaum, A. Nicolau, N. Hu, and M. Haghighat, ”Computer Vision for the Masses:  Bringing Computer Vision to the Open Web Platform”, Intel Parallel Universe Magazine, April 2018 issue.
Syndicated by EE Times.

2. S. Taheri, A. V. Veidenbaum, A. Nicolau, N. Hu, and M. Haghighat, ”OpenCV.js: Computer Vision Processing for the Open Web Platform”, ACM MMSys’18.

3. S. Taheri Bringing the Power of SIMD.js to gl-matrix, Mozilla Hacks Blog, 2015.
```

#### WebRTCBench
WebRTC is an HTML5 API that allows browsers to establish a peer-to-peer connection for transferring data and media content via JavaScript APIs. This functionality enables broad range of new applications to emerge and is going to revolutionize Web communication. WebRTCBench is a benchmark suite to provide quantitative comparison of WebRTC implementations across different browsers and architectures. Its main goal is to help in detecting performance bottlenecks of different implementations across operating systems and architectures. It also includes a database interface for storing measurement results. The benchmark was supported by a generous grant from Intel Corporation. 

Related publication:

```
S. Taheri, L. Beni, A. V. Veidenbaum, A. Nicolau , R. Cammarota, Jianlin Qiu, Qiang Lu and M. Haghighat, ”WebRTCBench:  Performance Assessment of WebRTC Implementations”, ACM/IEEE ESTIMEDIA’15.
```

Supported by Intel Corp.



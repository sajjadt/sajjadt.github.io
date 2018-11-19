---
layout: page
title: Research
comments: true
---

While at UC Irvine I was involved in three research projects:

#### FPGA Acceleration of Computer Vision Algorithms
Field Programmable Gate Arrays (FPGA)s are promising solutions for meeting the computation cost of computer vision algorithms. However, vision algorithms are difficult to translate to FPGA bitstream efficiently. Even, effcient CPU implementation is often a challenging task and requires a lot of expertise. In this research project I developed a framework for translating high-level vision algorithms (described by dataflow graphs) to efficient FPGA implementaion (described in OpenCL). It enables computer vision developers to quickly develop, verify and test their algorithms on FPGA platforms.

Related publication:

```
1. S. Taheri, P. Behnam, E. Bozorgzadeh, A. V. Veidenbaum, A. Nicolau, ”AFFIX: Automatic Acceleration Framework for FPGA Implementation of OpenVX Vision Algorithms”, ACM/SIGDA FPGA’19.

2. S.  Taheri,  J.  Heo,  P.  Behnam,  A.  V.  Veidenbaum,  A.  Nicolau,  ”Acceleration Framework for FPGA Implementation of OpenVX Graph Pipelines”, IEEE FCCM’18.
```

This project is supported by Intel Corporation.


#### Computer Vision Processing for the Open Web Platform

OpenCV.js brings years of OpenCV development in computer vision processing to the web with high efficiency. It provides a collection of carefully selected computer vision functions ranging from image processing, object detection, video analysis, features extraction, deep neural networks, etc. ![pum_cover]({{site.url}}/assets/pum_32_cover.png){:style="float: right;margin-left: 15px;margin-top: 15px;width: 300px;"}Thanks to JavaScript portability, for the first time, a large collection of vision functions can be used not only on web browsers but also on embedded devices (e.g. IOTs using Node.js) and Desktop application development (e.g. Electron framework. Combined with recent web technologies, it helps in realizing novel web applications and experiences such as emerging virtual and augmented reality more efficiently.



In addition, we have developed expansive online resources to help developers and researchers learn more about OpenCV.js and computer vision in general that can be accessed at:


<!-- 
OpenCV.js documentation and tutorials
OpenCV.js demos
OpenCV.js can also be used in Node.js based environments. It is published on NPM. -->



Relatd publications:

```
1. S. Taheri, A. V. Veidenbaum, A. Nicolau, N. Hu, and M. Haghighat, ”Computer Vision for the Masses:  Bringing Computer Vision to the Open Web Platform”, Intel Parallel Universe Magazine, April 2018 issue. Syndicated by EE Times.

2. S. Taheri, A. V. Veidenbaum, A. Nicolau, N. Hu, and M. Haghighat, ”OpenCV.js: Computer Vision Processing for the Open Web Platform”, ACM MultiMedia Systems'18.

3. S. Taheri Bringing the Power of SIMD.js to gl-matrix, Mozilla Hacks Blog, 2015.
```
This project is supported by Intel Corporation.

#### Performance Assesment of WebRTC Implementations
WebRTC is a set of HTML5 APIs for peer-to-peer data communication between web applications. This functionality has revolutionize the web communication and has led to emergenace of broad range of novel applications. ![A Typical WebRTC System]({{site.url}}/img/webrtcsys.png){:style="float: right;margin-left: 10px;margin-top: 7px;width: 250px;"}WebRTCBench is a benchmark suite to provide quantitative comparison of WebRTC implementations across different browsers and architectures. Its main goal is to help in detecting performance bottlenecks in early stages of WebRTC.

Related publication:

```
S. Taheri, L. Beni, A. V. Veidenbaum, A. Nicolau , R. Cammarota, Jianlin Qiu, Qiang Lu and M. Haghighat, ”WebRTCBench:  Performance Assessment of WebRTC Implementations”, ACM/IEEE ESTIMEDIA’15.
```

This project was supported by Intel Corporation.



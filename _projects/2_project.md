---
layout: page
title: Custom Processor Implemented on FPGA for Image Downsampling
description: A course project in EN3030 Circuits and Systems Design
img: /assets/img/processor_algo.png
importance: 2
category: undergrad course projects
---

Field Programmable Gate Array is a versatile platform for digital design. In this course project, a custom built processor was developed on FPGA in order to downsample an image. 

The algorithm was first designed and simulated on MATLAB to verify its credibility.Then the processor requirements such as the number of registers, buses, data memory size, instruction memory size, word sizes etc was determined alongside with the Instruction Set Architecture (ISA) and the Assembly codes. After the processor specifications were fixed the coding was completed using Verilog HDL which was followed by debugging and testing on hardware. 

An RS232 cable (UART based) was used to establish the communication between the PC and the FPGA. Python scripts were used to mediate the data transmitting and data receiving. 

Report  :   [[Report]](https://drive.google.com/open?id=1xgl0GBk0ieSggIGnXlHOPpIifrswnAO-)

Grade   :   4.2/4.2

Code    :   [[GitHub]](https://github.com/Laknath1996/Image-Downsampling-Processor-Design) 

<iframe width="480" height="270" src="https://www.youtube.com/embed/ZEHNLUbt3R4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

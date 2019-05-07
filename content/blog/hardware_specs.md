---
title: "GPU Hardware Specs Manual"
date: 2019-05-07T14:43:07Z
draft: false
---

NVIDIA GTX 1050
This GPU is built using NVIDIA's Pascal architecture, a successor of Maxwell which was introduced in 2016.

### General Specs

* GPU Architecture: Pascal
* CUDA Cores: 640
* Standard Memory: 2GB GDDR5
* Memory Speed: 7GB/s
* Memory Interface Width: 128 bit
* Memory Bandwidth (GB/s): 112
* Base Clock: 1354 Mhz
* Boost Clock: 1455 Mhz

### Supported Technologies

* CUDA
* 3DVision
* Physix
* NVDIA G-Synch
* ShadoWorks
* OpenGL

### Display & Resolution

* Max Resolution 7680*4320@60Hz
* Ports: DP1.4, HDMI 2.0b, Duallink-DVI
* Multimonitor: Yes
* HDCP: 2.2

### Power & Thermal

The GPU has a tiny TDP (Thermal Design Power) of just 75W)

* Max GPU Temperarture: 95 Degrees Centigrade
* Card Power: 75W
* Recomended Power Supply: 300W+

### What are 640 CUDA Cores?

CUDA is a parallel computing platform and application programming interface (API) model created by Nvidia,
which allows software developers and software engineers to use a CUDA-enabled graphics processing unit (GPU)
for general purpose processing. GPU Cores are parrarel processors responsible for processing all the data
that is fed in and out of the GPU.

CUDA cores on the other hand are similar to CPU cores BUT cannot fetch instructions, cannot decode instructions,
cannot access memory. CAN process large datasets. CPU's have several cores but GPU have thousands or cores.

An NVIDIA GPU that has more CUDA cores does not mean that it more powerful than one with less CUDA cores. This
is only true if they are from a similar family.

### GPU Architecture



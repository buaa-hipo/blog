---
layout: post
title: Identifying Software and Hardware Inefficiency at Scale
summary: HELD IN CONJUNCTION WITH THE IEEE INTERNATIONAL CONFERENCE ON CLUSTER COMPUTING (CLUSTER 2025)
featured-img: emile-perron-190221
---

<font color=Blue>
When: 9:30 - 13:00, September 2nd, 2025
<br />
Where: Holyrood, John McIntyre Conference Center in Edinburgh, United Kingdom.
</font>

# Overview
Production HPC software and system is becoming increasingly complex due to its deep software abstractions 
as well as hardware hierarchies. Such software and system complexity usually leads to unexpected 
inefficiencies that are hard to detect and locate at large scale through manual inspection. Versatile 
profilers have revealed a promising way to detect the above inefficiencies with accurate 
root cause analysis for optimization guidance, which is vital to achieve superior performance for scientific 
applications running at extremely large scale. 


In this tutorial, we will present a series of works on various profilers that detect 
performance inefficiencies due to sub-optimal computation, communication and I/O occurring at large scale. After the presentation of each profiler, 
we will provide hands-on exercises to acquaint the audience with the usage of 
each profiler and show case the effectiveness of each profiler for guiding 
performance optimization. The tools demonstrated in this tutorial have already 
been open-sourced for public access ([MSToolkit](https://github.com/buaa-hipo/MSToolkit)).


This tutorial is expected to provide the audiences with the background of performance analysis,
illustrate the well known performance profilers and their limitations, and then present our large-scale tools. We hope after the tutorial the audiences can master
the usage of large-scale tools to pinpoint hardware and software inefficiencies.

---

# Audience and Prerequisites

The target audience of the tutorial can be identified as two categories: 1) **application developers**,
people who are interested in optimizing the performance of their applications by leveraging the
strength of performance analysis tools, and 2) **tool developers**, people who are interested in building
customized value profilers to pinpoint unrevealed hardware and software inefficiencies for guiding performance
optimization.

The audience is expected to have a solid understanding of C/C++ programming languages, and a
basic understanding of computer architecture. Not required, but the audiences with a preliminary
experience of performance analysis tools are preferred.

---

# Hardware and Software Requirements

- **Hardware:** There is no special hardware required by the tutorial. The only thing we expect the
audiences is to bring his/her own laptops. The laptop should have decent computation, memory
and storage capability to access the remote server to run the hands-on exercises.

- **Software:** The necessary software environments have already been installed on the remote server. The audiences only need to copy the source files for
the hands-on exercises from the shared file system to their own workspaces. After that, they can start with
the hands-on exercises right away. Note that the audiences shall install their own favorite terminals in advance in order to access the remote server.

---

# Program

Stage | Content | Presenters | Schedule
:-:|:-|:-:|:-:
1 | Performance Engineering in HPC from A Tool Perspective | Hailong Yang | 9:30-10:00
2 | [Introduction of High Performance Cluster at CNIC](https://github.com/buaa-hipo/vprofiler-tutorial-cluster24/blob/main/Cluster25-tutorial-CNIC.pdf) | Ningming Nie,<br> Yuhang Hu | 10:00-10:10
3 | [Tutorial: Detecting Performance Variance on Large-Scale Heterogeneous Systems](https://github.com/buaa-hipo/vprofiler-tutorial-cluster24/blob/main/CLUSTER25-Tutorial-GVARP-final.pdf) | Xin You | 10:10-11:00
4 | Break |  | 11:00-11:30 
5 | [Tutorial: Runtime Performance Inefficiency Detection and Program Debugging](https://github.com/buaa-hipo/vprofiler-tutorial-cluster24/blob/main/Cluster25-tutorial-Vaddr(1).pdf) | Ningming Nie,<br> Yuhang Hu | 11:30-12:00
6 | [Tutorial: MPI Communication Performance Modeling](https://github.com/buaa-hipo/vprofiler-tutorial-cluster24/blob/main/Cluster25-tutorial-H-Lop.pdf) | Ziheng Wang | 12:00-12:30
7 | Tutorial: Identifying Parallel I/O Performance Bottleneck Using IOP Tool | Genshen Chu | 12:30-13:00

---

# Organizers

- Hailong Yang, Beihang University
- Xin You, Beihang University
- Zhibo Xuan, Beihang University
- Ningming Nie, Yuhang Hu, Computer Network Information Center, Chinese Academy of Science
- Ziheng Wang, Xi'an Jiaotong University
- Genshen Chu, University of Science and Technology Beijing 

---

# Related Publications

- You X, Xuan Z, Yang H, et al. [GVARP: Detecting performance variance on large-scale heterogeneous systems[C]](https://ieeexplore.ieee.org/abstract/document/10793232)//SC24: International Conference for High Performance Computing, Networking, Storage and Analysis. IEEE, 2024: 1-16.
- Xuan Z, You X, Feng T, et al. [SimTrace: Exploiting Spatial and Temporal Sampling for Large-Scale Performance Analysis[J]](https://dl.acm.org/doi/full/10.1145/3720544). ACM Transactions on Architecture and Code Optimization, 2025, 22(2): 1-26.
- Xuan Z, Sun X, You X, et al. [Identifying Performance Inefficiencies of Parallel Program With Spatial and Temporal Trace Analysis[J]](https://ieeexplore.ieee.org/abstract/document/10982439). IEEE Transactions on Parallel and Distributed Systems, 2025.
- Wang Z, Chen H, Cai W, et al. [C-Lop: Accurate contention-based modeling of MPI concurrent communication[J]](https://www.sciencedirect.com/science/article/abs/pii/S0167819122000278). Parallel Computing, 2022, 111: 102925.

---

# Questions

For questions about this tutorial, please contact Xin You (youxin2015@buaa.edu.cn) and Zhibo Xuan(xzb@buaa.edu.cn).

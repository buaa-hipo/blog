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
-------- | ----- | ----- | ----
1 | Introduction of Performance Analysis <br>and Profiling Tools in HPC | Hailong Yang | 9:30-10:00
2 | Introduction of High Performance Cluster<br> at CNIC | Ningming Nie,<br> Yuhang Hu | 10:00-10:10
3 | Tutorial: Detecting Performance Variance<br> on Large-Scale Heterogeneous Systems | Xin You | 10:10-11:00
4 | Break |  | 11:00-11:30 
5 | Tutorial: A Runtime Performance Variance<br> Detection & Diagnosis Tool | Ningming Nie,<br> Yuhang Hu | 11:30-12:00
6 | Tutorial: MPI communication performance<br> modeling based on supercomputer network<br> | Ziheng Wang | 12:00-12:30
7 | Tutorial: xxx| Genshen Chu | 12:30-13:00

---

# Organizers

- Hailong Yang, Beihang University
- Xin You, Beihang University
- Zhibo Xuan, Beihang University
- Ningming Nie, Shunde Li, Computer Network Information Center, Chinese Academy of Science
- Ziheng Wang, Xi'an Jiaotong University
- Genshen Chu, University of Science and Technology Beijing 

---

# Related Publications

- You X, Xuan Z, Yang H, et al. [GVARP: Detecting performance variance on large-scale heterogeneous systems[C]](https://ieeexplore.ieee.org/abstract/document/10793232)//SC24: International Conference for High Performance Computing, Networking, Storage and Analysis. IEEE, 2024: 1-16.

---

# Questions

For questions about this tutorial, please contact Xin You (youxin2015@buaa.edu.cn) and Zhibo Xuan(xzb@buaa.edu.cn).

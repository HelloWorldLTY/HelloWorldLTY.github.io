---
permalink: /
title:"                                                      Highlight Projects"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

AWGAN: A Powerful Batch Correction Model for scRNA-seq Data
======
![Example](/images/flowchart00.jpg)
![Example](/images/flowchart01.jpg)
Abstract: With the advancement of technology, we can generate and access large-scale, high dimensional and diverse genomics data, especially through single-cell RNA sequencing (scRNA-seq). However, integrative downstream analysis from multiple scRNA-seq datasets remains challenging due to batch effects. In this paper, we focus on scRNA-seq data integration and propose a new deep learning framework based on Wasserstein Generative Adversarial Network (WGAN) combined with an attention mechanism to reduce the differences among batches. We also discuss the limitations of the existing methods and demonstrate the advantages of our new model from both theoretical and practical aspects, advocating the use of deep learning in genomics research.

Bidirectional Prediction Model for Transcriptomics and Proteomics
======
![Example](/images/process.jpg)
Abstract: The major contribution of this work is to initially establish the transformation model between transcriptomics data and proteomics data. We proposed a model based on end-to-end learning strategy and encoder-decoder structure to predict its corresponding Antiboth-derived Tag data based on any single cell RNA sequence data, on the premise that the data used for training should come from the same tissue. We utilized the CITE-seq data and REAP-seq data for experiments and obtained promising results.


Deep Learning based Scheduling Sequence Generation Algorithm
======
Abstract: The manpower scheduling problem is a kind of critical combinational optimization problem. Researching solutions to scheduling problems can improve the efﬁciency of companies, hospitals, and other work units. This paper proposes a new model combined with deep learning to solve the multi-shift manpower scheduling problem based on the existing research. This model ﬁrst solves the objective function’s optimized value according to the current constraints to ﬁnd the plan of employee arrangement initially. It will then use the scheduling table generation algorithm to obtain the scheduling result in a short time. Moreover, the most prominent feature we propose is that we will use the neural network training method based on the time series to solve long-term and long-period scheduling tasks and obtain manpower arrangement. The selection criteria of the neural network and the training process are also described in this paper. We demonstrate that our model can make a precise forecast based on the improvement of neural networks. This paper also discusses the challenges in the neural network training process and obtains enlightening results after getting the arrangement plan. Our research shows that neural networks and deep learning strategies have the potential to solve similar problems effectively.


Operation System Competition
======
I would like to thank my lovely and clever teammates at first: [Lian Xinyu](https://xinyulian.tech), Lou Jiaqi and [Zhu Zhongbo](https://github.com/zzb66666666x).

![Example](/images/desktop.jpg)

In ECE 391, we design a operation system (HarmoniOS) from a frame with almost nothing. The process can be divided into five steps: 1. Design Interrupt Descriptor Table， Real Time Clock (RTC) and keyboard response. 2. Design driver components, including terminal, file system and RTC virtualization. 3. Implement 11 system calls (including execute, halt, etc.). 4. Increase the variety of system calls. 5. Complete task scheduling structure (we utilize robin algorithm). After finishing the above five basic tasks, we also take part in a competition for extra credits, which means we can design more interesting functions for our operation syste ([demo](https://xinyulian.tech/project/system-kernel/)). 

Finally, our OS can support the following functions:

**HarmoniOS FUNCTION LIST**

**BASIC FUNCTION**

(a) Support basic interrupt (keyboard, rtc, pit, etc.).

(b) Support read-only file system.

(c) Support basic system call.

(d) Support three terminals at most and process switch function.

**VGA RELATED**

(a) Allow to switch VGA mode 16 color and VGA mode 32 color.

(b) Provide background picture for desktop.

(c) Support animation of system entry.

(d) Support using mouse (by clicking **left button**) and keyboard (by pressing **ALT+F1/F2/F3/F4**) to switch different terminals and desktop.

(e) Support status bar display.

(f) Support cursor display.

**DEVICE RELATED**

(a) Support Peripheral Component Interconnect (PCI) bus.

(b) Support a speaker.

(c) Support mouse.

(d) Support receiving the system time from CMOS and print it on the status bar.

**COMMAND RELATED**

(a) Support auto-complete function for command (by pressing **tab**).

(b) Support history information buffer, whose maximum limit is 135 (by using **arrow up** and **arrow down**).
 
**SIGNAL RELATED**

(a) Provide a common API for idt content.

(b) Support five different signal mechanism.

(c) Enable system call: set signal handler and signal return.

**SYSTEM CALL RELATED**

(a) Support music play function (**beep**).

(b) Support random number generation, whose form is a guessing game (**random**).

(c) Support checking the status of running process.







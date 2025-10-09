---
permalink: /
title:   "                                    Highlight Projects"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


News: I am on the job market! Any recommendations for TTAP and Research Scientist positions are welcomed! PaSCient goes to Cell Systems, big congs to the team! <!-- Several papers accepted by NeurIPS and NPJ Digital Medicine, big congs to all co authors and see you at SD!-->  <!-- Papers accepted by Nature Biomedical Engineering and Cell Patterns! Big congs to all co authors!--> <!-- One paper accepted by Nature Communications! Big congs to Tinglin, Lijun, and Yingxin! One paper accepted by Cell Reports Methods! Big congs to Jia! --> <!-- One paper accepted by Genome Biology! Big congs to Wenxin! --> <!-- We are organizing New England NLP Meeting 2025, please refer our website for details: https://nenlp.github.io/spr2025/ ! -->  <!-- News: One paper accepted by Nature Communications! Big congs to Xiao and Tinyi!  --> <!-- News: I will join Broad Institute as a visiting scholar this summer, see you at Boston! --> <!-- News: One paper accepted by RECOMB 2025 for oral presentation! Big congs to all the co-authors! -->
======

Learning multi-cellular representations of single-cell transcriptomics data enables characterization of patient-level disease states
======
![Example](/images/pascient_pre.png)
Abstract: Single-cell RNA-seq (scRNA-seq) has become a prominent tool for studying human biology and disease. The availability of massive scRNA-seq datasets and advanced machine learning techniques has recently driven the development of single-cell foundation models that provide informative and versatile cell representations based on expression profiles. However, to understand disease states, we need to consider entire tissue ecosystems, simultaneously considering many different interacting cells. Here, we tackle this challenge by generating \emph{patient-level} representations derived from multi-cellular expression context measured with scRNA-seq of tissues. We develop PaSCient, a novel model that employs a multi-level representation learning paradigm and provides importance scores at the individual cell and gene levels for fine-grained analysis across multiple cell types and gene programs characteristic of a given disease. We apply PaSCient to learn a disease model across a large-scale scRNA-seq atlas of 24.3 million cells from over 5,000 patients. Comprehensive and rigorous benchmarking demonstrates the superiority of PaSCient in disease classification and its multiple downstream applications, including dimensionality reduction, gene/cell type prioritization, and patient subgroup discovery.

Evaluating the Utilities of Foundation Models in Single-cell Data Analysis
======
![Example](/images/singlecell_llm.png)
Abstract: Foundation Models (FMs) have made significant strides in both industrial and scientific domains. In this paper, we evaluate the performance of FMs for single-cell sequencing data analysis through comprehensive experiments across eight downstream tasks pertinent to single-cell data. Overall, the top FMs include scGPT, Geneformer, and CellPLM by considering model performances and user accessibility among ten single-cell FMs. However, by comparing these FMs with task-specific methods, we found that single-cell FMs may not consistently excel than task-specific methods in all tasks, which challenges the necessity of developing foundation models for single-cell analysis. In addition, we evaluated the effects of hyper-parameters, initial settings, and stability for training single-cell FMs based on a proposed \textbf{scEval} framework, and provide guidelines for pre-training and fine-tuning, to enhance the performances of single-cell FMs. Our work summarizes the current state of single-cell FMs, points to their constraints and avenues for future development, and offers a freely available evaluation pipeline to benchmark new models and improve method development.

ResPAN: a powerful batch correction model for scRNA-seq data through residual adversarial networks
======
![Example](/images/RESPAN_total.jpg)
Abstract: In this article, we propose a light-structured deep learning framework called **ResPAN** for scRNA-seq data integration. ResPAN is based on Wasserstein Generative Adversarial Network (WGAN) combined with random walk mutual nearest neighbor pairing and fully skip-connected autoencoders to reduce the differences among batches. We also discuss the limitations of existing methods and demonstrate the advantages of our model over seven other methods through extensive benchmarking studies on both simulated data under various scenarios and real datasets across different scales. Our model achieves leading performance on both batch correction and biological information conservation and maintains scalable to datasets with over half a million cells [link](https://respan.readthedocs.io/).

Operation System Competition
======
I would like to thank my lovely and clever teammates at first: [Lian Xinyu](https://xinyulian.tech), Lou Jiaqi and [Zhu Zhongbo](https://github.com/zzb66666666x).

![Example](/images/desktop.jpg)

In ECE 391, we design a operation system (HarmoniOS) from a frame with almost nothing. The process can be divided into five steps: 1. Design Interrupt Descriptor Table, Real Time Clock (RTC) and keyboard response. 2. Design driver components, including terminal, file system and RTC virtualization. 3. Implement 11 system calls (including execute, halt, etc.). 4. Increase the variety of system calls. 5. Complete task scheduling structure (we utilize robin algorithm). After finishing the above five basic tasks, we also take part in a competition for extra credits, which means we can design more interesting functions for our operation system ([demo](https://github.com/Alex-Lian/HarmoniOS)). 

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







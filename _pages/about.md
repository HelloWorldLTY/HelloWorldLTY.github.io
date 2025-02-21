---
permalink: /
title:   "                                    Highlight Projects"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

News: I will join Broad Institute as a visiting scholar this summer, see you at Boston! <!-- News: One paper accepted by RECOMB 2025 for oral presentation! Big congs to all the co-authors! -->
======

Learning multi-cellular representations of single-cell transcriptomics data enables characterization of patient-level disease states
======
![Example](/images/pascient_pre.png)
Abstract: Single-cell RNA-seq (scRNA-seq) has become a prominent tool for studying human biology and disease. The availability of massive scRNA-seq datasets and advanced machine learning techniques has recently driven the development of single-cell foundation models that provide informative and versatile cell representations based on expression profiles. However, to understand disease states, we need to consider entire tissue ecosystems, simultaneously considering many different interacting cells. Here, we tackle this challenge by generating \emph{patient-level} representations derived from multi-cellular expression context measured with scRNA-seq of tissues. We develop PaSCient, a novel model that employs a multi-level representation learning paradigm and provides importance scores at the individual cell and gene levels for fine-grained analysis across multiple cell types and gene programs characteristic of a given disease. We apply PaSCient to learn a disease model across a large-scale scRNA-seq atlas of 24.3 million cells from over 5,000 patients. Comprehensive and rigorous benchmarking demonstrates the superiority of PaSCient in disease classification and its multiple downstream applications, including dimensionality reduction, gene/cell type prioritization, and patient subgroup discovery.

Evaluating the Utilities of Foundation Models in Single-cell Data Analysis
======
![Example](/images/singlecell_llm.png)
Abstract: Foundation Models (FMs) have made significant strides in both industrial and scientific domains. In this paper, we evaluate the performance of FMs for single-cell sequencing data analysis through comprehensive experiments across eight downstream tasks pertinent to single-cell data. Overall, the top FMs include scGPT, Geneformer, and CellPLM by considering model performances and user accessibility among ten single-cell FMs. However, by comparing these FMs with task-specific methods, we found that single-cell FMs may not consistently excel than task-specific methods in all tasks, which challenges the necessity of developing foundation models for single-cell analysis. In addition, we evaluated the effects of hyper-parameters, initial settings, and stability for training single-cell FMs based on a proposed \textbf{scEval} framework, and provide guidelines for pre-training and fine-tuning, to enhance the performances of single-cell FMs. Our work summarizes the current state of single-cell FMs, points to their constraints and avenues for future development, and offers a freely available evaluation pipeline to benchmark new models and improve method development.

CVQVAE: A representation learning based method for multi-omics single cell data integration
======
![Example](/images/model_figure_cvqvae.jpg)
Abstract: The rapid development of second-generation sequencing has brought about a
significant increase in the amount of omics data. Integrating and analyzing these
single-cell datasets is a challenging problem. In this paper, we propose a new
model, called as **CVQVAE**, based on a cross-trained VAE, and strengthened by the
Vector Quantization technique for multi-omics data integration. CVQVAE projects
data vectors from different omics onto a common latent space in such a way that (1)
similar cells are close in the latent space and (2) the original biological information
present in each of the omics (including cell cycle and trajectory) are preserved. Our
model is trained and optimized solely based on the multi-omics data and requires
no additional information such as cell-type labels. We empirically demonstrate the
stability and efficiency of our method in data integration (alignment) on datasets
from a recent competition on Open Problems in Single Cell Analysis.


ResPAN: a powerful batch correction model for scRNA-seq data through residual adversarial networks
======
![Example](/images/RESPAN_total.jpg)
Abstract: In this article, we propose a light-structured deep learning framework called **ResPAN** for scRNA-seq data integration. ResPAN is based on Wasserstein Generative Adversarial Network (WGAN) combined with random walk mutual nearest neighbor pairing and fully skip-connected autoencoders to reduce the differences among batches. We also discuss the limitations of existing methods and demonstrate the advantages of our model over seven other methods through extensive benchmarking studies on both simulated data under various scenarios and real datasets across different scales. Our model achieves leading performance on both batch correction and biological information conservation and maintains scalable to datasets with over half a million cells [link](https://respan.readthedocs.io/).

Bidirectional Prediction Model for Transcriptomics and Proteomics
======
![Example](/images/process.jpg)

Abstract: The major contribution of this work is to initially establish the transformationmodel between transcriptomics data and proteomics data. On the premise that thedata used for training should come from the same tissue, we proposed a modelbased on end-to-end learning strategy and a bidirectional encoder-decoder structure(BiAE) to predict the corresponding Antibody-derived Tag data based on anysingle-cell RNA sequence data and to predict single-cell RNA sequence data basedon its corresponding Antibody-derived Tag data. We utilized the CITE-seq dataand REAP-seq data for experiments and obtained promising results.

Specular Reflection Detection and Removal Based on Deep Neural Network for Endoscope Images
======
![Example](/images/flowchart_srtp.png)
Abstract: Specular reflections have always been undesirable when processing endoscope vision for clinical purpose. Scene afflicted with strong specular reflection could result in visual confusion for the operation of surgical robot. In this paper, we propose a novel model based on deep learning framework, known as Surgical Fix Deep Neural Network (SFDNN). This model can effectively detect and fix the reflection points in different surgical videos hence opening up a whole new approach in handling undesirable specular reflections.

Deep Learning based Scheduling Sequence Generation Algorithm
======
![Example](/images/flowchart_didi.png)
Abstract: The manpower scheduling problem is a kind of critical combinational optimization problem. Researching solutions to scheduling problems can improve the efﬁciency of companies, hospitals, and other work units. This paper proposes a new model combined with deep learning to solve the multi-shift manpower scheduling problem based on the existing research. This model ﬁrst solves the objective function’s optimized value according to the current constraints to ﬁnd the plan of employee arrangement initially. It will then use the scheduling table generation algorithm to obtain the scheduling result in a short time. Moreover, the most prominent feature we propose is that we will use the neural network training method based on the time series to solve long-term and long-period scheduling tasks and obtain manpower arrangement. The selection criteria of the neural network and the training process are also described in this paper. We demonstrate that our model can make a precise forecast based on the improvement of neural networks. This paper also discusses the challenges in the neural network training process and obtains enlightening results after getting the arrangement plan. Our research shows that neural networks and deep learning strategies have the potential to solve similar problems effectively.

Operation System Competition
======
I would like to thank my lovely and clever teammates at first: [Lian Xinyu](https://xinyulian.tech), Lou Jiaqi and [Zhu Zhongbo](https://github.com/zzb66666666x).

![Example](/images/desktop.jpg)

In ECE 391, we design a operation system (HarmoniOS) from a frame with almost nothing. The process can be divided into five steps: 1. Design Interrupt Descriptor Table， Real Time Clock (RTC) and keyboard response. 2. Design driver components, including terminal, file system and RTC virtualization. 3. Implement 11 system calls (including execute, halt, etc.). 4. Increase the variety of system calls. 5. Complete task scheduling structure (we utilize robin algorithm). After finishing the above five basic tasks, we also take part in a competition for extra credits, which means we can design more interesting functions for our operation system ([demo](https://github.com/Alex-Lian/HarmoniOS)). 

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







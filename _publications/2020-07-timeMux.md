---
title: "Time Multiplexing via Circuit Folding"
collection: publications
permalink: /publication/2020-07-timeMux
excerpt: "The structural and functional circuit folding methods are proposed to address time multiplexing in multi-FPGA system. These methods may potentially help alleviate the bottleneck of limited inter-chip I/O bandwidth."
date: 2020-07-23
venue: "Proceedings of the Design Automation Conference (DAC)"
paperurl: ""
citation: "P.-C. Chien and J.-H. R. Jiang, &quot;Time Multiplexing via Circuit Folding,&quot; <i>in Proceedings of the Design Automation Conference (DAC)</i>, 2020."
---
Abstract:  
Time multiplexing is an important technique to overcome the bandwidth bottleneck of limited input-output pins in FPGAs.
Most prior work tackles the problem from a physical design standpoint to minimize the number of cut nets or Time Division Multiplexing (TDM) ratio through circuit partitioning or routing.
In this work, we formulate a new orthogonal approach at the logic level to achieve time multiplexing through structural and functional circuit folding.
The new formulation provides a smooth trade-off between bandwidth and throughput.
Experiments show the effectiveness of the structural method and improved optimality of the functional method on look-up-table and flip-flop usage.

Click the links to view the paper [[IEEE *Xplore*](https://ieeexplore.ieee.org/document/9218552) &#124; [ACM DL](https://dl.acm.org/doi/10.5555/3437539.3437575) &#124; [PDF](http://po-chun-chien.github.io/files/papers/dac20_tm.pdf)], the presentation [[slides](http://po-chun-chien.github.io/files/slides/dac20_tm_slides.pdf) &#124; [video](https://drive.google.com/file/d/10DEV1OVY9kAqCohN_r78ly3z4wCUE18V/view?usp=sharing)], the [source code](https://github.com/NTU-ALComLab/ext-folding) and the project [page](https://po-chun-chien.github.io/projects/4.tm/).

To cite the paper, you may use the following BibTex entry.
<pre><code>@inproceedings{Chien:DAC:2020,
    author      = {Po-Chun Chien and Jie-Hong Roland Jiang},
    title       = {Time Multiplexing via Circuit Folding},
    booktitle   = {Proceedings of the Design Automation Conference (DAC)},
    year        = {2020}
}</code></pre>
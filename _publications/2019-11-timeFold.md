---
title: "Time-Frame Folding: Back to the Sequentiality"
collection: publications
permalink: /publication/2019-11-timeFold
excerpt: "Time-frame folding is formulated as the reverse operation of time-frame expansion. This method has the ability in circuit size compaction and applications in logic synthesis domains."
date: 2019-11-05
venue: "Proceedings of the International Conference on Computer-Aided Design (ICCAD)"
paperurl: ""
citation: "P.-C. Chien and J.-H. R. Jiang, &quot;Time-frame Folding: Back to the Sequentiality,&quot; <i>in Proceedings of the International Conference of Computer-Aided Design (ICCAD)</i>, 2019."
---
Abstract:  
In this paper we formulate time-frame folding (TFF) as the reverse operation of time-frame unfolding (TFU), or commonly known as time-frame expansion in automatic test pattern generation (ATPG) and (un)bounded model checking.
While the latter converts a sequential circuit into a combinational one with respect to some expansion bound of $k$ time-frames, the former attempts the opposite.
TFF arises naturally in the context of testbench generation and bounded strategy generalization, and yet remains unstudied.
Unlike TFU, TFF can be highly nontrivial as the subcircuit of each time-frame can be distinct.
We propose an algorithm that finds a minimum-state finite state machine consistent with the input-output behavior of the combinational circuit under folding.
Empirical evaluation of our method demonstrates its ability in circuit size compaction and suggests potential use in different application domains.

Click the links to view the paper [[IEEE *Xplore*](https://ieeexplore.ieee.org/document/8942078) &#124; [PDF](http://po-chun-chien.github.io/files/papers/iccad19_tff.pdf)], the [slides](http://po-chun-chien.github.io/files/slides/iccad19_tff_slides.pdf), the [source code](https://github.com/NTU-ALComLab/ext-folding) and the project [page](https://po-chun-chien.github.io/projects/3.tff/).

To cite the paper, you may use the following BibTex entry.
<pre><code>@inproceedings{Chien:ICCAD:2019,
    author      = {Po-Chun Chien and Jie-Hong Roland Jiang},
    title       = {Time-Frame Folding: Back to the Sequentiality},
    booktitle   = {Proceedings of the International Conference of Computer-Aided Design (ICCAD)},
    year        = {2019}
}</code></pre>
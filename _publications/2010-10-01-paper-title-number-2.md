---
title: "On Semi-Blind Source Separation-Based Approaches
to Nonlinear Echo Cancellation Based on Bilinear
Alternating Optimization"
collection: publications
permalink: /publication/2024-05-30-paper-BiAEC-number-2
excerpt: #''
date: 2020-12-18
venue: 'IEEE/ACM Trans. on Audio, Speech, and Lang. Process. '
slidesurl: #'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://XianruiWang.github.io/files/biaec_2024.pdf'
citation: #'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Acoustic echo cancellation (AEC) is a crucial task in
full duplex communications. As conventional linear filtering approaches are ineffective to deal with double-talk, various semi-blind
source separation (SBSS)-based AEC algorithms are deceived,
most of which are formulated and implemented in the frequency domain based on the multiplicative transfer function (MTF) model for
computational efficiency. To avoid large latency and in order to deal
with loudspeaker nonlinearities, the convolutive transfer function
(CTF) model and odd power series expansion are leveraged, which
are employed by numerous SBSS-based nonlinear AEC (SBSSNAEC) algorithms. Conventional SBSS-NAEC methods estimate
the series expansion coefficients and the CTF filter simultaneously
making the number of free parameters to estimate large. Hence, the
corresponding algorithms are computationally expensive and are
difficult to optimize. In this work, we propose to decouple the series
expansion coefficients and the CTF filters into a bilinear form and
present a bilinear alternating optimization framework for estimating the model parameters. An alternating iterative projection (AIP)
algorithm and an alternating element-wise iterative source steering
(AEISS) algorithm are proposed. As the bilinear representation
consists of less parameters compared to the conventional methods,
the proposed algorithms not only improve the AEC performance
but also reduce the computational complexity, which is validated
by comprehensive simulations and experiments.
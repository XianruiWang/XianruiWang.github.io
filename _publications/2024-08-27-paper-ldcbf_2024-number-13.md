---
title: "LOW ALGORITHMIC DELAY IMPLEMENTATION OF CONVOLUTIONAL BEAMFORMER FOR ONLINE JOINT SOURCE SEPARATION AND DEREVERBERATION"
collection: publications
permalink: /publication/2024-08-27-paper-ldcbf_2024-number-13
excerpt: #''
date: 2024-08-27
venue: 'EUSIPCO'
slidesurl: #'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://XianruiWang.github.io/files/ld_cbf_2024.pdf'
citation: #'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Blind-audio-source-separation (BASS) techniques, particularly those with low latency, play an important role in a wide range of real-time systems, e.g., hearing aids, in-car hand-free voice communication, real-time human-machine interaction, etc. Most existing BASS algorithms are deduced to run on batch mode, and therefore large latency is unavoidable. Recently, some online algorithms were developed, which achieve separation on a frame-by-frame basis in the short-time-Fourier-transform (STFT) domain and the latency is significantly reduced as compared to those batch methods. However, the latency with these algorithms may still be too long for many real-time systems to bear. To further reduce latency while achieving good separation performance, we propose in this work to integrate a weighted prediction error (WPE) module into a non-causal sample-truncating-based independent vector analysis (NST-IVA). The resulting algorithm can maintain the algorithmic delay as NST-IVA if the delay with WPE is appropriately controlled while achieving significantly better performance, which is validated by simulations.
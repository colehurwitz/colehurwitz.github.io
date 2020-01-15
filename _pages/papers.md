---
layout: archive
title: "Publications"
permalink: /papers/
author_profile: true
---
<p>
<a href="https://papers.nips.cc/paper/8720-scalable-spike-source-localization-in-extracellular-recordings-using-amortized-variational-inference"><b>Scalable Spike Source Localization in Extracellular Recordings using Amortized Variational Inference</b></a>.&nbsp;<b>Cole L. Hurwitz</b>, Kai Xu, Akash Srivastava, Alessio P. Buccino, Matthias H. Hennig. <i> Advances in Neural Information Processing Systems 32 (NeurIPS 2019)</i>.
</p>

Determining the positions of neurons in an extracellular recording is useful for investigating the functional properties of the underlying neural circuitry. In this work, we present a Bayesian modelling approach for localizing the source of individual spikes on high-density, microelectrode arrays. To allow for scalable inference, we implement our model as a variational autoencoder and perform amortized variational inference. We evaluate our method on both biophysically realistic simulated and real extracellular datasets, demonstrating that it is more accurate than and can improve spike sorting performance over heuristic localization methods such as center of mass.

<p>
   [<a href="https://papers.nips.cc/paper/8720-scalable-spike-source-localization-in-extracellular-recordings-using-amortized-variational-inference">NeurIPS</a>
   | <a href="https://www.biorxiv.org/content/10.1101/656389v1">bioRxiv</a>
   | <a href="https://github.com/colehurwitz/decay_model">Source Code</a>

 ]
</p>

<p>
<a href="https://arxiv.org/abs/1809.01051"><b>Scaling Spike Detection and Sorting for Next Generation Electrophysiology
</b></a>.&nbsp; Matthias H. Hennig, <b>Cole L. Hurwitz</b>, Martino Sorbaro. <i> In Vitro Neuronal Networks - From Culturing Methods to Neuro-Technological Applications, Springer International Publishing.</i> 2019.
</p>

Reliable spike detection and sorting, the process of assigning each detected spike to its originating neuron, is an essential step in the analysis of extracellular electrical recordings from neurons. The volume and complexity of the data from recently developed large scale, high density microelectrode arrays and probes, which allow recording from thousands of channels simultaneously, substantially complicate this task conceptually and computationally. This chapter provides a summary and discussion of recently developed methods to tackle these challenges, and discuss the important aspect of algorithm validation, and assessment of detection and sorting quality.
<p>
   [<a href="https://arxiv.org/abs/1809.01051">arXiv</a>

 ]
</p>

# Preprints

<p>
<a href="https://www.biorxiv.org/content/10.1101/2020.01.14.900688v1?rss=1"><b>SpikeForest: reproducible web-facing ground-truth validation of automated neural spike sorters</b></a>.&nbsp;Jeremy F Magland, James J Jun, Elizabeth Lovero, <b>Cole L. Hurwitz</b>, Alessio P. Buccino, Samuel Garcia, Alex H Barnett. bioRxiv 2020.
</p>

Spike sorting is a crucial but time-intensive step in electrophysiological studies of neuronal activity. While there are many popular software packages for spike sorting, there is little consensus about which are the most accurate under different experimental conditions. SpikeForest is an open-source and reproducible software suite that benchmarks the performance of automated spike sorting algorithms across an extensive, curated database of electrophysiological recordings with ground truth, displaying results interactively on a continuously-updating website. With contributions from over a dozen participating laboratories, our database currently comprises 650 recordings (1.3 TB total size) with around 35,000 ground-truth units. These data include extracellular recordings paired with intracellular voltages, state-of-the-art simulated recordings, and hybrid synthetic datasets. Ten of the most frequently used modern spike sorting codes are wrapped under a common Python framework and evaluated on a compute cluster using an automated pipeline. SpikeForest validates and documents community progress in automated spike sorting, and guides neuroscientists to an optimal choice of sorter and parameters for a wide range of probes and brain regions.

<p>
   [<a href="https://www.biorxiv.org/content/10.1101/2020.01.14.900688v1?rss=1">bioRxiv</a>
   | <a href="https://spikeforest.flatironinstitute.org/">Website</a>
   | <a href="https://github.com/flatironinstitute/spikeforest2">Source Code</a>

 ]
</p>

<p>
<a href="https://www.biorxiv.org/content/10.1101/796599v1"><b>SpikeInterface, a unified framework for spike sorting</b></a>.&nbsp;Alessio P. Buccino<sup>1</sup>, <b>Cole L. Hurwitz</b><sup>1</sup>, Jeremy Magland, Samuel Garcia, Joshua H. Siegle, Roger Hurwitz, Matthias H. Hennig. bioRxiv 2019. 1. equal contribution
</p>

Given the importance of understanding single-neuron activity, much development has been directed towards improving the performance and automation of spike sorting. These developments, however, introduce new challenges, such as file format incompatibility and reduced interoperability, that hinder benchmarking and preclude reproducible analysis. To address these limitations, we developed SpikeInterface, a Python framework designed to unify preexisting spike sorting technologies into a single codebase and to standardize extracellular data file operations. With a few lines of code and regardless of the underlying data format, researchers can: run, compare, and benchmark most modern spike sorting algorithms; pre-process, post-process, and visualize extracellular datasets; validate, curate, and export sorting outputs; and more. In this paper, we provide an overview of SpikeInterface and, with applications to both real and simulated extracellular datasets, demonstrate how it can improve the accessibility, reliability, and reproducibility of spike sorting in preparation for the widespread use of large-scale electrophysiology.

<p>
   [<a href="https://www.biorxiv.org/content/10.1101/796599v1">bioRxiv</a>
   | <a href="https://github.com/SpikeInterface">Source Code</a>

 ]
</p>

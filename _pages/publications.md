---
layout: archive
title: "Papers"
permalink: /papers/
author_profile: true
---

# Publications
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
<a href="https://www.biorxiv.org/content/10.1101/796599v1"><b>SpikeInterface, a unified framework for spike sorting</b></a>.&nbsp;Alessio P. Buccino, <b>Cole L. Hurwitz*</b>, Jeremy Magland, Samuel Garcia, Joshua H. Siegle, Roger Hurwitz, Matthias H. Hennig. bioRxiv 2019.
</p>

Given the importance of understanding single-neuron activity, much development has been directed towards improving the performance and automation of spike sorting. These developments, however, introduce new challenges, such as file format incompatibility and reduced interoperability, that hinder benchmarking and preclude reproducible analysis. To address these limitations, we developed SpikeInterface, a Python framework designed to unify preexisting spike sorting technologies into a single codebase and to standardize extracellular data file operations. With a few lines of code and regardless of the underlying data format, researchers can: run, compare, and benchmark most modern spike sorting algorithms; pre-process, post-process, and visualize extracellular datasets; validate, curate, and export sorting outputs; and more. In this paper, we provide an overview of SpikeInterface and, with applications to both real and simulated extracellular datasets, demonstrate how it can improve the accessibility, reliability, and reproducibility of spike sorting in preparation for the widespread use of large-scale electrophysiology.

<p>
   [<a href="https://www.biorxiv.org/content/10.1101/796599v1">bioRxiv</a>
   | <a href="https://github.com/SpikeInterface">Source Code</a>

 ]
</p>

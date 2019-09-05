---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<p>
<a href="https://arxiv.org/abs/1905.12375"><b>Scalable Spike Source Localization in Extracellular Recordings using Amortized Variational Inferences</b></a>.&nbsp;<b>Cole L Hurwitz</b>, Kai Xu, Akash Srivastava, Alessio Paolo Buccino, Matthias Hennig. <i>Conference on Neural Information Processing Systems (NeurIPS)</i>  2019.
</p>

Extracellular recordings using modern, dense probes provide detailed footprints of action potentials (spikes) from thousands of neurons simultaneously. Inferring the activity of single neurons from these recordings, however, is a complex blind source separation problem, complicated both by the high intrinsic data dimensionality and large data volume. Despite these complications, dense probes can allow for the estimation of a spike's source location, a powerful feature for determining the firing neuron's position and identity in the recording. Here we present a novel, generative model for inferring the source of individual spikes given observed electrical traces. To allow for scalable, efficient inference, we implement our model as a variational autoencoder and perform amortized variational inference. We evaluate our method on biophysically realistic simulated datasets, showing that our method outperforms heuristic localization methods such as center of mass and can improve spike sorting performance significantly. We further apply our model to real data to show that it is an effective, interpretable tool for analyzing large-scale extracellular recordings.

<p>
   [<a href="https://www.biorxiv.org/content/10.1101/656389v1">bioRxiv</a>
   | <a href="https://github.com/colehurwitz/vae_spike_localization">Source Code</a>

 ]
</p>

<p>
<a href="https://arxiv.org/abs/1809.01051"><b>Scaling Spike Detection and Sorting for Next Generation Electrophysiology
</b></a>.&nbsp; Matthias H. Hennig, <b>Cole L Hurwitz</b>, Martino Sorbaro. <i> In Vitro Neuronal Networks - From Culturing Methods to Neuro-Technological Applications, Springer International Publishing.</i> 2018.
</p>

Reliable spike detection and sorting, the process of assigning each detected spike to its originating neuron, is an essential step in the analysis of extracellular electrical recordings from neurons. The volume and complexity of the data from recently developed large scale, high density microelectrode arrays and probes, which allow recording from thousands of channels simultaneously, substantially complicate this task conceptually and computationally. This chapter provides a summary and discussion of recently developed methods to tackle these challenges, and discuss the important aspect of algorithm validation, and assessment of detection and sorting quality.
<p>
   [<a href="https://arxiv.org/abs/1809.01051">arXiv</a>

 ]
</p>

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### Publications
<p>
<a href="https://arxiv.org/abs/1905.12375"><b>Scalable Spike Source Localization in Extracellular Recordings using Amortized Variational Inferences</b></a>.&nbsp;Cole L. Hurwitz, Kai Xu, Akash Srivastava, Alessio Paolo Buccino, Matthias Hennig. In <i>Conference on Neural Information Processing Systems (NeurIPS)</i>.  2019.
</p>

<p>
   [<a href="https://www.biorxiv.org/content/10.1101/656389v1">bioRxiv</a>
	| <a href="javascript:toggle('bibhurwitz19localize', 'bib_link_hurwitz19localize', 'bib')"  id="bib_link_srivastava17lda">bib</a>
	| <a href="javascript:toggle('abshurwitz19localize', 'abs_link_hurwitz19localize', 'abstract')" 
 ]
</p>

<div id="divhurwitz19localize"></div>
<div style="display:none;" id="abshurwitz19localize"><div class="abstract">Extracellular recordings using modern, dense probes provide detailed footprints of action potentials (spikes) from thousands of neurons simultaneously. Inferring the activity of single neurons from these recordings, however, is a complex blind source separation problem, complicated both by the high intrinsic data dimensionality and large data volume. Despite these complications, dense probes can allow for the estimation of a spike's source location, a powerful feature for determining the firing neuron's position and identity in the recording. Here we present a novel, generative model for inferring the source of individual spikes given observed electrical traces. To allow for scalable, efficient inference, we implement our model as a variational autoencoder and perform amortized variational inference. We evaluate our method on biophysically realistic simulated datasets, showing that our method outperforms heuristic localization methods such as center of mass and can improve spike sorting performance significantly. We further apply our model to real data to show that it is an effective, interpretable tool for analyzing large-scale extracellular recordings.</div></div>

<div style="display:none;" id="bibhurwitz19localize"><pre class="bibtex">@article{hurwitz2019scalable,
  title={Scalable Spike Source Localization in Extracellular Recordings using Amortized Variational Inference},
  author={Hurwitz, Cole L and Xu, Kai and Srivastava, Akash and Buccino, Alessio Paolo and Hennig, Matthias},
  journal={arXiv preprint arXiv:1905.12375},
  year={2019}
}
</pre></div>

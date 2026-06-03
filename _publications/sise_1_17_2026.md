---
title: "Towards noise-robust speech inversion through multi-task learning with speech enhancement"
collection: publications
permalink: /publications/sise_1_17_2026
excerpt: "This work introduces a novel multi-task learning framework that jointly integrates speech enhancement and speech inversion to improve the robustness of articulatory feature estimation in noisy environments. By leveraging shared self-supervised speech representations from WavLM-Large, the proposed approach simultaneously enhances speech signals while estimating oral vocal tract variables, velopharyngeal activity (nasalance), and source features such as pitch, periodicity and Aperiodicity. Unlike traditional pipelines that treat speech enhancement as a separate preprocessing step, our framework enables both tasks to benefit from joint optimization, leading to substantial performance gains under challenging noise conditions. Experimental results demonstrate strong robustness across babble and non-babble noise scenarios, achieving significant improvements in speech inversion accuracy at low signal-to-noise ratios, with potential applications in speech disorder assessment and real-world speech analysis systems.
"
date: 2026-01-17
venue: 
short: 'ICASSP 2026'
paperurl: 'https://arxiv.org/abs/2601.14516'
teaser: '../images/SISE.png'
authors:  <b>Saba Tabatabaee</b>, Carol Espy-Wilson"
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
project: "https://raaslab.org/projects/LLM_Context_Estimation/"
redirect_from: 
  - /lancar
---

<p style="text-align:center;">
<img src="../images/nasality.png" width="800">
</p>

## Abstract
<div style="text-align: justify"> SRecent studies demonstrate the effectiveness of Self Su-
pervised Learning (SSL) speech representations for Speech
Inversion (SI). However, applying SI in real-world scenarios
remains challenging due to the pervasive presence of back-
ground noise. We propose a unified framework that integrates
Speech Enhancement (SE) and SI models through shared
SSL-based speech representations. In this framework, the
SSL model is trained not only to support the SE module in
suppressing noise but also to produce representations that are
more informative for the SI task, allowing both modules to
benefit from joint training. At a Signal-to-Noise Ratio of –5
dB, our method for the SI task achieves relative improvements
over the baseline of 80.95% under babble noise and 38.98%
under non-babble noise, as measured by the average Pearson
product–moment correlation across all estimated parameters..</div>
<br>

| Paper                                         
|---------------------------------------------------------------------------------------------------------|
| [**Speech Enhancement and Speech Inversion through Multi-Task Framework**](https://arxiv.org/abs/2601.14516) |

<br>

Please cite our work if you found it useful,

```
@article{tabatabaee2026towards,
  title={Towards noise-robust speech inversion through multi-task learning with speech enhancement},
  author={Tabatabaee, Saba and Espy-Wilson, Carol},
  journal={arXiv preprint arXiv:2601.14516},
  year={2026}
}

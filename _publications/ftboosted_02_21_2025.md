---
title: "FT-Boosted SV: Towards Noise Robust Speaker Verification for English Speaking Classroom Environments"
collection: publications
permalink: /publications/ftboosted_02_21_2025
excerpt: "In this study, we explored speaker verification in real Englishspeaking classrooms, where both children and adults are
present. We demonstrated the effectiveness of finetuning pretrained models using a domain-specific, augmented dataset for
speaker verification tasks in noisy and challenging environments, such as classrooms. Our results show that this approach
significantly improves the performance of both the ECAPATDNN and x-vector models for children’s speech and classroom environments. We also found that the ECAPA-TDNN (FT-Boosted) model exhibited superior robustness, especially in handling variations in microphone configurations and classroom noise. Additionally, we propose that the optimal development set for finetuning speaker verification models is a combination of the MyST, CSLU, and CMU datasets, due to their diverse age range and speech styles. This diverse combination enables speaker verification models to generalize more effectively, improving their performance in real-world educational settings."
date: 2025-06-15
venue: 'Proc. in Interspeech 2025'
short: 'Interspeech 2025'
paperurl: 'https://www.isca-archive.org/interspeech_2025/tabatabaee25_interspeech.pdf'
teaser: '../images/ft.jpeg'
authors:  <b>Saba Tabatabaee</b>, Jing Liu, Carol Espy-Wilson"
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
redirect_from: 
  - /ft
---

<p style="text-align:center;">
<img src="../images/ft.jpeg" width="800">
</p>

## Abstract
<div style="text-align: justify"> Creating Speaker Verification (SV) systems for classroom settings that are robust to classroom noises such as babble noise is crucial for the development of AI tools that assist educational
environments. In this work, we study the efficacy of finetuning with augmented children datasets to adapt the x-vector and ECAPA-TDNN to classroom environments. We demonstrate that finetuning with augmented children’s datasets is powerful in that regard and reduces the Equal Error Rate (EER) of xvector and ECAPA-TDNN models for both classroom datasets and children speech datasets. Notably, this method reduces EER of the ECAPA-TDNN model on average by half (a 5% improvement) for classrooms in the MPT dataset compared to the ECAPA-TDNN baseline model. The x-vector model shows an 8% average improvement for classrooms in the NCTE dataset compared to its baseline.</div>
<br>

| Paper                                         
|---------------------------------------------------------------------------------------------------------|
| [**FT-Boosted**](https://www.isca-archive.org/interspeech_2025/tabatabaee25_interspeech.pdf) |

<br>

Please cite our work if you found it useful,

```
@inproceedings{tabatabaee25_interspeech,
  title     = {{FT-Boosted SV: Towards Noise Robust Speaker Verification for English Speaking Classroom Environments }},
  author    = {Saba Tabatabaee and Jing Liu and Carol Espy-Wilson},
  year      = {2025},
  booktitle = {{Interspeech 2025}},
  pages     = {2815--2819},
  doi       = {10.21437/Interspeech.2025-1002},
  issn      = {2958-1796},
}
```

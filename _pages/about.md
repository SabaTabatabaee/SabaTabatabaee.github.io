---
permalink: /
title: "Biography"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm Saba. I'm a **Ph.D. candidate in Electrical and Computer Engineering** at the [University of Maryland, College Park](https://umd.edu/), advised by Prof. [Carol Espy-Wilson](https://isr.umd.edu/clark/faculty/391/Carol-Espy-Wilson) in the [Speech Communication Lab](https://scl.umd.edu/), and a **Graduate Researcher in the EduNLP Lab at Stanford University**.

I build **speech and multimodal machine learning systems that hold up in the real world**: noisy classrooms, overlapping talkers, children's voices, and clinical populations. My work covers speech recognition, speaker diarization and verification, speech enhancement, and acoustic-to-articulatory speech inversion, using self-supervised speech models such as WavLM, wav2vec 2.0, and HuBERT. I also apply ML to biomedical signals and imaging (EEG, fMRI).

So far this has led to **10 peer-reviewed publications (9 first-author)** and **one pending patent**, developed with collaborators in clinical science, linguistics, and education. Full list on [Google Scholar](https://scholar.google.com/citations?user=d7tPM7MAAAAJ&hl=en).

> **On the job market:** I'm looking for full-time **research scientist / ML engineer** roles in speech, audio, and multimodal AI. If my work fits your team, I'd love to hear from you at [sabatbtbee@gmail.com](mailto:sabatbtbee@gmail.com).

## Selected Results

- **Classroom ASR + diarization (Stanford):** end-to-end system for child and adult speech that outperforms Gemini 2.5 Pro, WhisperX, Sortformer, VibeVoice-ASR, and Nemotron 3 on DER, cpWER, and WDER.
- **Noise-robust speaker verification:** self-supervised and contrastive learning on unlabeled classroom audio, giving a **24% relative EER reduction** over ECAPA-TDNN.
- **Speech inversion (patent pending):** estimates lip, tongue, velum, and glottal activity from audio alone.
  - A **non-invasive alternative to nasopharyngoscopy** for children with velopharyngeal insufficiency, validated against clinical gold standards.
  - **81% / 39% relative gains** in unseen babble / non-babble noise via multi-task learning with speech enhancement.
  - Trained only on English, it **generalizes to Sinhala, Russian, and French**.
- **Multimodal emotion recognition:** fuses speech, facial action units, and articulatory features.

## Research Interests

- Speech Recognition & Speaker Diarization
- Speaker Verification
- Speech Enhancement & Noise Robustness
- Speech Inversion
- Self-Supervised & Multimodal Learning
- Biomedical Signal Processing (EEG, fMRI)

## News

<style>
td, th {
  border: none !important;
  padding-top: 4px;
  padding-bottom: 4px;
  vertical-align: top;
}
</style>

<div style="max-height: 300px; overflow-y: auto;">
<table style="border-collapse: collapse; font-size: 17px; border: none; width: 100%;">
<col width="120px">
  <!-- TODO: replace "2026" with the exact month for these items -->
  <tr><td><b>2026</b></td><td>Paper on language-agnostic speech inversion accepted at <b>Interspeech 2026</b></td></tr>
  <tr><td><b>2026</b></td><td>Paper published in <b>The Journal of the Acoustical Society of America (JASA)</b></td></tr>
  <tr><td><b>2026</b></td><td>Received the <b>ASA</b> and <b>LabPhon 20</b> student scholarships</td></tr>
  <tr><td><b>May 2026</b></td><td>Joined the <b>EduNLP Lab at Stanford University</b> to work on classroom ASR and diarization</td></tr>
  <tr><td><b>Apr 2026</b></td><td>Paper accepted at <b>LabPhon 20</b> (oral presentation)</td></tr>
  <tr><td><b>Mar 2026</b></td><td>Abstract accepted at <b>ASA 2026</b> (poster)</td></tr>
  <tr><td><b>Jan 2026</b></td><td>Paper accepted at <b>ICASSP 2026</b> (poster)</td></tr>
  <tr><td><b>Aug 2025</b></td><td>Abstract accepted at <b>ASA 2025</b> (poster)</td></tr>
  <tr><td><b>Aug 2025</b></td><td>Received a <b>University of Maryland</b> student scholarship</td></tr>
  <tr><td><b>Jul 2025</b></td><td>Paper accepted at <b>ASRU 2025</b></td></tr>
  <tr><td><b>Jul 2025</b></td><td>Paper accepted in <b>JSLHR</b></td></tr>
  <tr><td><b>Jun 2025</b></td><td>Received the <b>BSMCS</b> student scholarship</td></tr>
  <tr><td><b>May 2025</b></td><td>Three papers accepted at <b>Interspeech 2025</b></td></tr>
  <tr><td><b>Apr 2025</b></td><td>Two abstracts accepted at <b>BSMCS 2025</b> (poster)</td></tr>
  <tr><td><b>Feb 2025</b></td><td>Abstract accepted at <b>NCVS 2025</b> (oral presentation)</td></tr>
  <tr><td><b>Aug 2022</b></td><td>Started my Ph.D. at the <b>University of Maryland, College Park</b></td></tr>
</table>
</div>

<br>

## Selected Publications <a id="pub"></a>

{% include base_path %}
{% include archive-compact.html %}

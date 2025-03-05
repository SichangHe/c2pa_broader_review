# GenAI: Problems Introduced and Countermeasures


## Deepfake

Accessible, scalable and performant

### Disinformation

- Influence democratic process \[4, 8, 11\]
- Mislead public perception and belief through social media \[4, 6, 8\]
- Erode trust in media, democracy, authority, artwork, archival and
  legal evidence; “truth decay” \[3, 9–11\]

------------------------------------------------------------------------

**Countermeasures**

- C2PA to attest content is real \[1, 4, 11\]
  - 👍 Source and history \[3, 6, 7, 10\]
    - Traceability and trust for not being tempered \[5\]
  - 👎 Can be spoofed by taking photo with photo \[12\]
  - 👎 Privacy: disclose sensitive information, but mechanisms exist
    \[5\]
  - 👎 Can be stripped, is usually stripped \[4\]
  - 👎 Need wide adoption \[1, 4\]
  - 👎 Provenance does not imply trust \[7\]

------------------------------------------------------------------------

- Preserve content on searchable blockchain \[1, 2, 6, 8, 9\]
  - 👎 complex to implement; need wide adoption
- Watermarking by content creator \[6\]
  - 👍 detect tempering, protect copyright
- JPEG Trust: “trust report” for user to evaluate trust \[7\]
  - 👍 Directly address trust
  - 👎 Implementation details unclear; privacy

------------------------------------------------------------------------

### Cybercrime

- Video conference scam targeting business \[6, 9\]
- Video promotion scam targeting individual \[6, 9\]
  - Video romance scam \[9\]
- Personal attack: porn, fake speech, cyberbullying \[6, 7\]
  - Identity theft \[3, 7, 9\]

**Countermeasures**

- Cloud provider limit bad actor \[6\]

## Generation not for faking

- Bias in generation \[3, 7\]
- Intellectual property laundry \[1, 3, 4\]
- Not transparent or explainable, thus problem for regulation \[3\]
- Privacy and consent of training data \[1, 3, 4\]

------------------------------------------------------------------------

**Countermeasures**

- Explainable AI (XAI) \[3, 9\]
- Bias mitigation and de-identification of training data \[3\]
- NFT of generation with authenticity metadata, ORA (Ownership, Rights,
  Attribution) \[1, 4\]
- Visual matching for generation \[1\]

## General countermeasures

- Public awareness and education \[6, 12\]
- Detection
  - Human technique \[3\]
  - ML detection model, e.g., GAN
    - 👍 Much more accurate than human \[3\]
    - 👍 Can be improved constantly \[12\]
    - 👎 Cannot outcompete generator \[6, 9\]
  - Physiological signal analysis for video, e.g., blood flow \[9\]
  - Multi-modal detection \[9\]

------------------------------------------------------------------------

- Detection (cont.)
  - Watermarking training data \[3, 4\]
  - Watermarking generated content \[9, 10\]
    - 👎 Can be stripped, tempered or faked \[4, 10\]
- Fingerprinting: search by perceived hash \[1, 4\]
  - 👍 Recover stripped metadata; some resilience to tempering \[4\]
  - 👎 Sensitive to editing \[4\]
  - 👎 Need access to content database \[4\]
  - 👎 Scalability and privacy concern \[4\]

------------------------------------------------------------------------

- Similarity search (correlation) \[4\]
  - 👎 May not reflect causality \[4\]
- Organizational effort: partnership \[6\]
- Legal framework and global standard \[6, 9\]

## References

<div id="refs" class="references csl-bib-body" entry-spacing="0">

<div id="ref-balan2023ekila" class="csl-entry">

<span class="csl-left-margin">\[1\]
</span><span class="csl-right-inline">Balan, K., Agarwal, S., Jenni, S.,
Parsons, A., Gilbert, A. and Collomosse, J. 2023. EKILA: Synthetic media
provenance and attribution for generative art. *Proceedings of the
IEEE/CVF conference on computer vision and pattern recognition* (2023),
913–922.</span>

</div>

<div id="ref-bureacua2024blockchain" class="csl-entry">

<span class="csl-left-margin">\[2\]
</span><span class="csl-right-inline">Bureacă, E. and Aciobăniței, I.
2024. A blockchain blockchain-based framework for content provenance and
authenticity. *2024 16th international conference on electronics,
computers and artificial intelligence (ECAI)* (2024), 1–5.</span>

</div>

<div id="ref-bushey2023ai" class="csl-entry">

<span class="csl-left-margin">\[3\]
</span><span class="csl-right-inline">Bushey, J. 2023. AI-generated
images as an emergent record format. *2023 IEEE international conference
on big data (BigData)* (2023), 2020–2031.</span>

</div>

<div id="ref-collomosse2024authenticity" class="csl-entry">

<span class="csl-left-margin">\[4\]
</span><span class="csl-right-inline">Collomosse, J. and Parsons, A.
2024. To authenticity, and beyond! Building safe and fair generative AI
upon the three pillars of provenance. *IEEE Computer Graphics and
Applications*. 44, 3 (2024), 82–90.</span>

</div>

<div id="ref-fotos2023ensuring" class="csl-entry">

<span class="csl-left-margin">\[5\]
</span><span class="csl-right-inline">Fotos, N. and Delgado, J. 2023.
Ensuring privacy in provenance information for images. *2023 24th
international conference on digital signal processing (DSP)* (2023),
1–5.</span>

</div>

<div id="ref-kharvi2024understanding" class="csl-entry">

<span class="csl-left-margin">\[6\]
</span><span class="csl-right-inline">Kharvi, P.L. 2024. Understanding
the impact of AI-generated deepfakes on public opinion, political
discourse, and personal security in social media. *IEEE Security &
Privacy*. (2024).</span>

</div>

<div id="ref-mo2023towards" class="csl-entry">

<span class="csl-left-margin">\[7\]
</span><span class="csl-right-inline">Mo, J., Kang, X., Hu, Z., ZHou,
H., Li, T. and Gu, X. 2023. Towards trustworthy digital media in the
aigc era: An introduction to the upcoming IsoJpegTrust standard. *IEEE
Communications Standards Magazine*. 7, 4 (2023), 2–5.</span>

</div>

<div id="ref-rainey2023trait" class="csl-entry">

<span class="csl-left-margin">\[8\]
</span><span class="csl-right-inline">Rainey, J., Elawady, M.,
Abhayartne, C. and Bhowmik, D. 2023. TRAIT: A trusted media distribution
framework. *2023 24th international conference on digital signal
processing (DSP)* (2023), 1–5.</span>

</div>

<div id="ref-romero5031627deepfake" class="csl-entry">

<span class="csl-left-margin">\[9\]
</span><span class="csl-right-inline">Romero-Moreno, F. Deepfake fraud
detection: Safeguarding trust in generative ai. *Available at SSRN
5031627*.</span>

</div>

<div id="ref-shoker2023confidence" class="csl-entry">

<span class="csl-left-margin">\[10\]
</span><span class="csl-right-inline">Shoker, S., Reddie, A.,
Barrington, S., Booth, R., Brundage, M., Chahal, H., Depp, M., Drexel,
B., Gupta, R., Favaro, M., et al. 2023. Confidence-building measures for
artificial intelligence: Workshop proceedings. *arXiv preprint
arXiv:2308.00862*. (2023).</span>

</div>

<div id="ref-strickland2024election" class="csl-entry">

<span class="csl-left-margin">\[11\]
</span><span class="csl-right-inline">Strickland, E. 2024. This election
year, look for content credentials: Media organizations combat deepfakes
and disinformation with digital manifests. *IEEE Spectrum*. 61, 01
(2024), 24–27.</span>

</div>

<div id="ref-vilesov2024solutions" class="csl-entry">

<span class="csl-left-margin">\[12\]
</span><span class="csl-right-inline">Vilesov, A., Tian, Y.,
Sehatbakhsh, N. and Kadambi, A. 2024. Solutions to deepfakes: Can camera
hardware, cryptography, and deep learning verify real images? *arXiv
preprint arXiv:2407.04169*. (2024).</span>

</div>

</div>

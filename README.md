# The Influence of IQ on the Brain's Auditory Cortex Activation in Schizophrenia

🔗 **Live site:** [https://rhekacitra.github.io/capstone-website/](https://rhekacitra.github.io/capstone-website/)

## About

This website presents our capstone research investigating how cognitive ability (IQ) relates to auditory cortex activation during speech perception in individuals with schizophrenia. Using functional MRI data from [OpenNeuro](https://openneuro.org/datasets/ds004302/versions/1.0.0), we analyze brain responses to spoken words, sentences, and reversed speech across three participant groups:

- **AVH+** — Schizophrenia patients with auditory verbal hallucinations
- **AVH−** — Schizophrenia patients without recent auditory hallucinations
- **HC** — Healthy controls

The site walks through our introduction, data, methods, results (including interactive visualizations), and conclusions.

## Team

| Name | Contact |
|------|---------|
| Katrina Suherman |[ksuherman@ucsd.edu](mailto:ksuherman@ucsd.edu) |
| Paige Pagaduan | [ppagaduan@ucsd.edu](mailto:ppagaduan@ucsd.edu) |
| Rheka Narwastu | [rnarwastu@ucsd.edu](mailto:rnarwastu@ucsd.edu) |

**Mentors:** Armin Schwartzman, Gabriel Riegner

## Features

- Responsive single-page layout with smooth scroll navigation
- Interactive Plotly scatter plot (IQ vs. ROI Activation) with filters for contrast type, participant group, sex, and an IQ range slider
- Sections covering introduction, data source, methods, results, and conclusions

## Analysis Repository

The full reproducible fMRI analysis pipeline (FSL preprocessing, first/second-level analysis, ROI extraction) is maintained separately:

🔗 [IQ-Influence-on-Brain-Auditory-Cortex-in-Schizophrenia](https://github.com/rhekacitra/IQ-Influence-on-Brain-Auditory-Cortex-in-Schizophrenia)

## Data Source

> Soler-Vidal, J., et al. (2022). *Brain correlates of speech perception in schizophrenia patients with and without auditory hallucinations.* **PLOS ONE**.

Dataset available at: [OpenNeuro ds004302 v1.0.0](https://openneuro.org/datasets/ds004302/versions/1.0.0)

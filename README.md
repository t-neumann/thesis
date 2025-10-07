# Tobias Neumann — PhD Thesis

This repository contains the LaTeX sources, figures, and supplementary materials for my doctoral dissertation.

---

## 📘 Thesis Overview

| Field | Details |
|---|---|
| **Title** | *Recovery, quantification and error correction of nucleotide conversions in epitranscriptomics sequencing datasets* |
| **Author** | Dipl.-Ing. Tobias Neumann |
| **Degree** | Doctor of Philosophy (PhD) |
| **Institution** | University of Vienna |
| **Faculty / Field of Study** | Molecular Biosciences |
| **Degree Programme Code** | UA 794 620 490 |
| **Year / Place** | Vienna, 2023 |
| **Supervisor** | Univ.-Prof. Dr. Arndt von Haeseler |
| **Language** | English |
| **License / Usage** | © 2023 Tobias Neumann — all rights reserved unless otherwise stated |
| **u:theses ID / Repository** | 66620 — hosted in the University of Vienna’s electronic theses repository (u:theses) |

---

## 🧬 Abstract

The application of high-throughput sequencing methods to study RNA has revo-
lutionized our understanding of the transcriptome and opened up multiple avenues
to study its processes. A recent flavor are epitranscriptome sequencing technolo-
gies that detect naturally occurring or artificially introduced nucleotide modifica-
tions which can be employed as a means to study dynamic cellular processes such
as gene expression dynamics or splicing kinetics. These nucleotide conversions
are typically read out as mismatches during sequencing when mapped to a refer-
ence sequence and pose challenges to established reference-based read mapping
approaches that are typically designed to only tolerate mismatches in the range of
genetic variation and sequencing error.
In this thesis, we address this lack of appropriate methods by proposing a novel
strategy to robustly and accurately map and quantify nucleotide conversion con-
taining read sets. We apply our method to a novel epitranscriptomics sequencing
technology and demonstrate our method provides constant mapping rates even at
high conversion rates and is able to robustly quantify nucleotide conversions in an
unbiased manner.
In a complementary effort, we provide a specialized RNA-seq simulation frame-
work that models the introduction of nucleotide conversions in arbitrary mixes of
(partially) spliced transcript variants, thereby enabling a comprehensive evaluation
of biological entities and processes that are studied with epitranscriptome sequenc-
ing technologies. Using large-scale simulated datasets, we provide an extensive
benchmark of mapping accuracies of current popular read mapping tools, quan-
tify introduced biases and propose strategies to mitigate their impact on the final
biological interpretation of the respective readouts.

---

## 🧠 Related Work & Publications

- **Popitsch N\***, **Neumann T\***, von Haeseler A, & Ameres SL.  
  *[Splice_sim: a nucleotide-conversion enabled RNA-seq simulation and evaluation framework.](https://doi.org/10.1186/s13059-024-03313-8)*  
  *Genome Biology*, **25**, 166 (2024).  
  → [📘 DOI: 10.1186/s13059-024-03313-8](https://doi.org/10.1186/s13059-024-03313-8)  
  → [💻 GitHub: splice_sim](https://github.com/popitsch/splice_sim)

- **Neumann T**, Herzog VA, Muhar M, von Haeseler A, Zuber J, Ameres SL & Rescheneder P.  
  *[Quantification of experimentally induced nucleotide conversions in high-throughput sequencing datasets.](http://doi.org/10.1186/s12859-019-2849-7)*  
  *BMC Bioinformatics*, **20**(1), 258 (2019).  
  → [📘 DOI: 10.1186/s12859-019-2849-7](http://doi.org/10.1186/s12859-019-2849-7)  
  → [💻 GitHub: slamdunk](https://github.com/t-neumann/slamdunk)

These works expand upon and implement methods introduced or developed during the research for this thesis, focusing on RNA-seq data simulation and quantitative modeling of nucleotide conversions.

---

## 📁 Repository Structure

```
.
├── chapters/                        # Individual chapters, including abstract.tex, coverpage, etc.
├── img/                             # Figures, illustrations, plots
├── styles/                          # Custom LaTeX style files and packages
├── papers/                          # PDFs of papers resulting from this thesis
├── references.bib                   # Bibliography database
├── tobias_neumann_phd_thesis.tex    # Main LaTeX document
└── README.md
```

---

## 🧩 Keywords

- Epitranscriptomics  
- RNA Modifications  
- Nucleotide Conversions  
- Sequencing Error Correction  
- Computational Biology  
- Bioinformatics  
- Statistical Modeling  

---

## 🔗 Useful Links

- [University of Vienna – u:theses entry (ID 66620)](https://utheses.univie.ac.at/detail/66620/)
- [Personal website](https://t-neumann.github.io/)
- [Tobias Neumann on GitHub](https://github.com/t-neumann)  
- [Slamdunk](https://github.com/t-neumann/slamdunk)
- [splice_sim](https://github.com/popitsch/splice_sim)

---

## ⚙️ Build Instructions

To compile the thesis locally:

```bash
# If you have xelatex installed:
xelatex -pdf tobias_neumann_phd_thesis.tex
```

This should generate `thesis.pdf` in the repository root (or in your configured output folder).

---

## 📄 Citation

If you reference this thesis, a suggested citation is:

> Tobias Neumann (2023). *Recovery, quantification and error correction of nucleotide conversions in epitranscriptomics sequencing datasets.*  
> Doctoral thesis, University of Vienna. Supervisor: Univ.-Prof. Dr. Arndt von Haeseler.  
> u:theses ID 66620, University of Vienna’s electronic theses repository.

---

**Contact:** [tobias.neumann.at(at)gmail.com](mailto:tobias.neumann.at@gmail.com)

---

# Coffee-Rust-Fungal-Community

# Fungal Communities Associated with Coffee Leaf Rust

> An interactive scientific data analysis and visualization project exploring the fungal communities associated with *Hemileia vastatrix* (coffee leaf rust) using high-throughput ITS1 amplicon sequencing.

## Overview

This repository contains the analysis, visualizations, and interactive website developed to investigate fungal communities associated with coffee leaf rust pustules collected from *Coffea arabica* plantations in Costa Rica.

The project combines microbial ecology, bioinformatics, and data visualization to characterize fungal diversity and evaluate how environmental factors, particularly altitude and geographic location, influence fungal community composition.

The published analysis supports research on microbial interactions that may contribute to future biological control strategies against coffee leaf rust.(https://repositorio.sibdi.ucr.ac.cr/browse/author?value=Torres%20Rugama,%20Ariel%20Steven)

## Live Website

🌐 **Project Website**

https://arielbiotechcr.github.io/Coffee-Rust-Fungal-Community/fungal-communities-associated-with-the-coffee-rust.html

## Features

- Interactive visualizations of fungal community composition
- Diversity analyses of ITS1 metabarcoding data
- Alpha and beta diversity metrics
- Community composition plots
- Statistical analyses
- Publication-ready figures
- Responsive website generated from R Markdown / Quarto

## Technologies

- **R**
- **R Markdown**
- **phyloseq**
- **vegan**
- **ggplot2**
- **dplyr**
- **plotly**
- **htmlwidgets**
- **GitHub Pages**

## Scientific Background

Coffee leaf rust (*Hemileia vastatrix*) is one of the most economically important diseases affecting coffee production worldwide. This project investigates fungal taxa co-occurring within rust pustules to better understand microbial community structure and identify potential ecological interactions relevant for sustainable disease management.  [oai_citation:1‡PubMed](https://pubmed.ncbi.nlm.nih.gov/41866413/?utm_source=chatgpt.com)

## Repository Structure

```
├── data/                 # Input datasets
├── scripts/              # Analysis scripts
├── figures/              # Generated figures
├── docs/                 # GitHub Pages website
├── README.md
└── ...
```

*(Directory names may vary depending on the current repository organization.)*

## Results

The analysis includes:

- Taxonomic composition of fungal communities
- Relative abundance visualizations
- Diversity indices
- Ordination analyses (PCoA/NMDS)
- Community comparisons across sampling sites
- Environmental factor analyses

## Reproducibility

Clone the repository:

```bash
git clone https://github.com/ArielBiotechCR/Coffee-Rust-Fungal-Community.git
```

Open the R project or R Markdown files and install the required packages:

```r
install.packages(c(
  "phyloseq",
  "vegan",
  "ggplot2",
  "dplyr",
  "plotly",
  "htmlwidgets"
))
```

Run the analysis scripts to regenerate the figures and interactive website.

## Research Impact

This project demonstrates applications of:

- Microbial ecology
- Bioinformatics
- High-throughput sequencing analysis
- Ecological statistics
- Scientific visualization
- Reproducible research workflows

## Citation

If you use this repository, please cite the associated publication:

Torres-Rugama, A. (2024) Micobiota asociada a las hojas de plantas mutantes y variedades comerciales de café (Coffea arabica L.) infectadas con la roya anaranjada (Hemileia vastatrix Berk et Br) [Tesis de grado, Universidad de Costa Rica]. Repository SIBDI-UCR https://repositorio.sibdi.ucr.ac.cr/browse/author?value=Torres%20Rugama,%20Ariel%20Steven 

## Author

**Ariel Torres**

Biotechnology • Bioinformatics • Microbial Ecology • Data Science

GitHub: https://github.com/ArielBiotechCR

## License

This repository is intended for research and educational purposes. Please refer to the LICENSE file for licensing information.
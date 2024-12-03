# Microbiome time series data reveal predictable patterns of change


This repository contains the source code used to generate figures for the manuscript *Microbiome time series data reveal predictable patterns of change*  [DOI: 10.1128/spectrum.04109-23](https://journals.asm.org/doi/full/10.1128/spectrum.04109-23) . To utilize the methods described in the manuscript for your own research, please clone or download dynamo library from: https://github.com/paula078/dynamo_library 

## Overview

The gut microbiome plays a pivotal role in health and disease. Unlike cross-sectional studies, longitudinal approaches provide deeper insights into its temporal dynamics, crucial for precision medicine and targeted interventions like personalized diets or probiotic therapy.

In this study, we developed a statistical framework to analyze gut microbiome time series, offering tools for assessing microbial community dynamics, predictive modeling, stability classification, and clustering bacteria with similar temporal patterns. Using densly samples amplicon sequencing data from four healthy individuals, we identified six longitudinal regimes and explored functional relationships among bacterial clusters. 

Our findings highlight the healthy gut microbiome's stability, with limited fluctuations in specific bacterial subsets. This work advances understanding of microbiome dynamics, supporting innovative therapeutic strategies and fostering further research.

*Importance* : 

This project developed innovative methods to analyze gut microbiome time series data, offering fresh insights into its dynamic nature. Unlike many studies that focus on static snapshots, we found that the healthy gut microbiome is predictably stable over time, with only a small subset of bacteria showing significant changes. By identifying groups of bacteria with diverse temporal behaviors and clusters that change together, we pave the way for more effective probiotic therapies and dietary interventions, addressing the overlooked dynamic aspects of gut microbiome changes.

## Features

### 🌍 **Community-Level Microbiome Analysis**
Understand the broader structure of the microbiome with community-wide analysis, including **alpha diversity** calculations, which provide insights into the richness and evenness of microbial species in your samples. 

- **Alpha diversity**: Evaluate the overall health of the microbiome, as higher diversity is often linked to improved health outcomes.
- **Principal coordinate analysis (PCoA)**: Reveal distinct clusters for each subject’s microbiome.
- **Taxonomy**: Visualize taxonomy changes over time
- **Fourier Transform Analysis**: Automatically detect **seasonal patterns** in microbiome data, allowing for an understanding of how external factors affect the microbial community.
  
### 🔍 **Individual Species Analysis**
Track individual bacterial species over time to uncover their unique behaviors, stability, and responses to environmental changes.

- **Temporal stability**: Identify species that are stable over time versus those that fluctuate.
- **Correlation analysis**: Determine how different species interact with each other within the microbiome.
  
### 🔮 **Predictive Modeling with ARIMAX**
Forecast future changes in the microbiome using **ARIMAX models**, allowing you to predict how microbial communities may evolve under various conditions.

### 🔮 **Features clustering**
Cluster features that fluctuate together in time using compositional correlation and community detection approach.

## Citation

Microbiome time series data reveal predictable patterns of change
Z. Karwowska, P. Szczerbiak, T. Kosciolek.
Published in Microbiology Spectrum, 2024. DOI: 10.1128/spectrum.04109-23. 

https://journals.asm.org/doi/full/10.1128/spectrum.04109-23

# 🦠 Microbiome time series data reveal predictable patterns of change 🦠🔬


This repository contains the source code used to generate figures for the manuscript *Microbiome time series data reveal predictable patterns of change*  DOI: 10.1128/spectrum.04109-23. To utilize the methods described in the manuscript for your own research, please clone or download dynamo library from: https://github.com/paula078/dynamo_library 

## Overview

The human gut microbiome is crucial in health and disease. Longitudinal studies are becoming increasingly important compared to traditional cross-sectional approaches, as precision medicine and individualized interventions are coming to the forefront. Investigating the temporal dynamics of the microbiome is essential for comprehending its function and impact on health. This knowledge has implications for targeted therapeutic strategies, such as personalized diets or probiotic therapy. 

In this study, we focused on developing and implementing methods specifically designed for analyzing gut microbiome time series. Our statistical framework provides researchers with tools to examine the temporal behavior of the gut microbiome. Key features of our framework include statistical tests for time series properties, predictive modeling, classification of bacterial species based on stability and noise, and clustering analyses to identify groups of bacteria with similar temporal patterns. We analyzed dense amplicon sequencing time series from four generally healthy subjects. Using our developed statistical framework, we analyzed both the overall community dynamics and the behavior of individual bacterial species. We showed six longitudinal regimes within the gut microbiome and discussed their features. Additionally, we explored whether specific bacterial clusters undergo similar fluctuations, suggesting potential functional relationships and interactions within the microbiome. Our development of specialized methods for analyzing human gut microbiome time series significantly enhances the understanding of its dynamic nature and implications for human health. 

The guidelines and tools provided by our framework support scientists in studying the complex dynamics of the gut microbiome, fostering further research and advancements in microbiome analysis. The gut microbiome is integral to human health, influencing various diseases. Longitudinal studies offer deeper insights into its temporal dynamics compared to cross-sectional approaches. 

In this study, we developed a statistical framework for analyzing the time series of the human gut microbiome. This framework provides robust tools for examining microbial community dynamics over time. It includes statistical tests for time series properties, predictive modeling, classification of bacterial species based on stability and noise, and clustering analyses. Our approach significantly enhances the methodologies available to researchers, promoting further exploration and innovation in microbiome analysis.

*Importance* : This project developed innovative methods to analyze gut microbiome time series data, offering fresh insights into its dynamic nature. Unlike many studies that focus on static snapshots, we found that the healthy gut microbiome is predictably stable over time, with only a small subset of bacteria showing significant changes. By identifying groups of bacteria with diverse temporal behaviors and clusters that change together, we pave the way for more effective probiotic therapies and dietary interventions, addressing the overlooked dynamic aspects of gut microbiome changes.

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

## Citation

Microbiome time series data reveal predictable patterns of change
Z. Karwowska, P. Szczerbiak, T. Kosciolek.
Published in Microbiology Spectrum, 2024. DOI: 10.1128/spectrum.04109-23.

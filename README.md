# sex-differences
This repository contains R scripts used to analyze sex-specific microbial differences in the CRCbiome study, with a focus on sex-specific colorectal cancer–associated gut microbiome signatures.

The analyses support the manuscript:

Bucher-Johannessen et al.
Gut microbiome signatures of colorectal cancer development are more pronounced in women compared to men in a population-based screening cohort.
Available on [medRxiv](https://www.medrxiv.org/content/10.1101/2025.05.16.25327767v2.full).

## Overview

The scripts in this repository were used to perform statistical analyses and visualization of microbiome data stratified by sex, including diversity analyses, differential abundance testing, and multivariate statistics.

All analyses were performed in R (version 4.2.0).

## Data availability

This repository does not contain raw sequencing data.
Processed taxonomic tables was generated using biobakery3 (including MetaPhlAn3 and HUManN3).

## Software and packages

Analyses were conducted in R v4.2.0 using the following main packages:
- tidyverse (v1.3.1)
- rstatix (v0.7.0)
- nnet (v7.3-16)
- mice (v3.14.0)
- vegan (v2.5.7)
- MaAsLin2 (v1.12.0)

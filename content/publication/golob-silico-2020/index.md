---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: In silico benchmarking of metagenomic tools for coding sequence detection reveals
  the limits of sensitivity and precision
subtitle: ''
summary: ''
authors:
- Jonathan Louis Golob
- Samuel Schwartz Minot
tags:
- Bioinformatics
- Metagenomics
- Microbiome
categories: []
date: '2020-10-01'
lastmod: 2024-01-05T17:14:26-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2024-01-05T22:14:26.258852Z'
publication_types:
- '2'
abstract: 'BACKGROUND: High-throughput sequencing can establish the functional capacity
  of a microbial community by cataloging the protein-coding sequences (CDS) present
  in the metagenome of the community. The relative performance of different computational
  methods for identifying CDS from whole-genome shotgun sequencing is not fully established.
  RESULTS: Here we present an automated benchmarking workflow, using synthetic shotgun
  sequencing reads for which we know the true CDS content of the underlying communities,
  to determine the relative performance (sensitivity, positive predictive value or
  PPV, and computational efficiency) of different metagenome analysis tools for extracting
  the CDS content of a microbial community. Assembly-based methods are limited by
  coverage depth, with poor sensitivity for CDS at textless 5X depth of sequencing,
  but have excellent PPV. Mapping-based techniques are more sensitive at low coverage
  depths, but can struggle with PPV. We additionally describe an expectation maximization
  based iterative algorithmic approach which we show to successfully improve the PPV
  of a mapping based technique while retaining improved sensitivity and computational
  efficiency. CONCLUSION: Our benchmarking approach reveals the trade-offs of assembly
  versus alignment-based approaches and the relative performance of specific implementations
  when one wishes to extract the protein coding capacity of microbial communities.'
publication: '*BMC bioinformatics*'
doi: 10.1186/s12859-020-03802-0
---

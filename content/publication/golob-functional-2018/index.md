---
title: "Functional Analysis of Metagenomes by Likelihood Inference (FAMLI) Successfully Compensates for Multi-Mapping Short Reads from Metagenomic Samples"
date: 2018-04-01
publishDate: 2019-10-04T21:42:50.178665Z
authors: ["Jonathan L Golob", "Samuel S Minot"]
publication_types: ["4"]
abstract: "Short-read metagenomics use high-throughput sequencing to reveal the functional capability of microbial communities. The computational analysis of the raw short-read data is complicated by the shared functional domains in peptides, and the complex evolutionary origins of many peptides (including recombination and truncation), resulting in a given short read aligning equally well to many possible peptides.  We find that a short read known to be from one peptide will on average align equally well to about 160 other peptide sequences not present in the sample. Here we describe an iterative algorithmic approach to successfully map reads to their true origin peptides and introduce a software package FAMLI that implements this algorithm. We demonstrate that FAMLI is able to identify peptides from a wide variety of metagenomes with a consistent precision of about 0.8, and recall of about 0.6, while retaining O(n) runtimes. This compares favorably to alternative approaches, including de novo assembly (that results in superior precision, but much inferior recall and much larger computational resource needs as compared to FAMLI), or hybrid taxonomic-identification approaches (that results in less consistent performance for extremely novel communities, as compared to FAMLI). Addressing the problem of short reads aligning equally well to hundreds of more peptides than are truly present in a sample is a key challenge any successful short-read-metagenomics software must address. We present an effective approach to mitigate this problem and improve the accuracy of functional metagenomic analysis."
featured: true
publication: ""
url_pdf: "http://biorxiv.org/lookup/doi/10.1101/295352"
doi: "10.1101/295352"
---


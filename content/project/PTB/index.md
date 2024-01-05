---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Preterm Birth"
summary: "Identify pregnancies at risk for preterm birth using AI/ML models trained on microbiome data"
authors: []
tags: []
categories: []
date: 2024-01-04T17:32:05-05:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
## Overview

Preterm birth (PTB) is the leading cause of infant morbidity and mortality worldwide. Globally, every year approximately 11% of infants every year are born preterm, defined as birth prior to 37 weeks of gestation, totaling nearly 15 million births. In addition to the emotional and financial toll on families, preterm births result in higher rates of neonatal death, nearly 1 million deaths each year, and long-term health consequences for some children. Infants born preterm are at risk for a variety of adverse outcomes, such as respiratory illnesses, cerebral palsy, infections, and blindness, with infants born early preterm (i.e., before 32 weeks) at increased risk of these conditions. Thus, the ability to accurately identify women at risk for PTB is a first step in the development and implementation of treatment and prevention strategies.

## Team
- Jonathan Golob
- Marina Sirota
- Tomiko Oskotsky
- March of Dimes


## Approach

The vaginal microbiome has been extensively related to pregnancy outcomes, including preterm birth. Using novel techniques and software developed in the Golob Lab, we assembled a training set of vaginal microbiome data during pregnancy from nine technically, geographically, and biologically unique studies into a cohesive, biologically-meaningful, and generalizable features. We then shared these features to the AI/ML community as part of a crowdsourced DREAM challenge, asking teams to make their best possible models to predict preterm and early-preterm birth (PTB and ePTB respectively).

The performance of the models was established not on the training data, but instead on data from two independent validation studies not available to the model developers (or anyone) prior to the launch of the challenge. Again, using novel techniques and software developed in the Golob laboratory, this raw microbiome data was harmonized into the same set of training features post-hoc. 

## Findings so far

As reported in Cell Reports Medicine multiple AI/ML teams were able to create models with excellent predictive power, particularly in [identifying pregnancies at risk for early preterm birth](https://doi.org/10.1016/j.xcrm.2023.101350) from vaginal microbiome data.

The training data is available, and has been a key nucleus of futher studies including a novel approach for [dimensionality reduction](https://doi.org/10.1038/s41587-023-02033-x). 

## Next steps
We are now working towards clinical translation of the vaginal microbiome-based predictive models, both in prospective validation as well as software development with the paired establishment of quality control metrics needed for use in a clinical laboratory setting.
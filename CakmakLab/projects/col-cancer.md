---
---

# Colorectal Cancer Risk Screening 

This research explores the machine learning-based assessment of predisposition to colorectal cancer based on single nucleotide polymorphisms (SNP). Such a computational approach may be used as a risk indicator and an auxiliary diagnosis method that complements the traditional methods such as biopsy and CT scan. Moreover, it may be used to develop a low-cost screening test for the early detection of colorectal cancers to improve public health. We employ several supervised classification algorithms. We study SNPs in particular colorectal cancer-associated genomic loci that are located within DNA regions of 11 selected genes obtained from 115 individuals. We make the following observations: (i) random forest-based classifier using one-hot encoding and K-nearest neighbor (KNN)-based imputation performs the best among the studied classifiers with an F1 score of 89% and area under the curve (AUC) score of 0.96. (ii) One-hot encoding together with K-nearest neighbor-based data imputation increases the F1 scores by around 26% in comparison to the baseline approach which does not employ them. (iii) The proposed model outperforms a commonly employed state-of-the-art approach, ColonFlag, under all evaluated settings by up to 24% in terms of the AUC score. Based on the high accuracy of the constructed predictive models, the studied 11 genes may be considered a gene panel candidate for colon cancer risk screening (Cakmak et al. 2022).

{% capture col1 %}

{%
  include figure.html
  image="images/cakmaklab_project/col-cancer.svg"
%}

{% endcapture %}

{% include cols.html col1=col1 %}
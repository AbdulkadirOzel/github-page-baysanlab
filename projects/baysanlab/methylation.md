---
---

# Relation Of Methylation with Survival, p53 Mutation and Low Apoptosis in Cancer

One of the most crucial epigenetic processes that permits cells to specialize for certain functions in various organs is DNA methylation. DNA methylation can now be profiled at high throughput thanks to recent technological advancements. In this work, we examined the Total Methylation departure (TMD), which assesses the overall departure for each sample and is used as a diagnostic of epigenetic instability in cancer. We used TCGA pan-cancer data for 32 different tumor types with 6948 samples, which contains copy number, mutation, methylation, and expression profiles. We used in-depth survival studies that take into account potential confounding factors including age, subclone count, copy number alterations, mutations, and expression variation to determine the impact of methylation deviation on illness progression.

TMD is substantially related with poor prognosis in terms of overall survival and disease-specific survival, according to survival analysis for pan-cancer studies (FDR 0.005, FDR 0.0001). The enhanced tumor aggressiveness brought on by high levels of genetic instability may help to explain this. When we looked at each kind of cancer separately, methylation variation was shown to be positively correlated with the probability of mortality for 5 cancer types, which is consistent with the findings for all cancer types. One of the most prevalent somatic modifications in a variety of cancer types is the p53 mutation. Methylation variation showed a high negative link with immunological activity and apoptosis and a substantial positive correlation with p53 mutations. These findings provide light on the interaction between genomic instability and p53 mutations and imply that TMD may be a key indicator in the development of cancer.


{% capture col1 %}

{%
  include figure.html
  image="images/methylation_project.png"
%}

{% endcapture %}

{% include cols.html col1=col1 %}
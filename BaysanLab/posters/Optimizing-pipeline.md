---
---

# Optimizing pipeline combinations for cancer sequencing

---

{% capture col1 %}

{%
  include figure.html
  image="images/third-project.png"
  link= "https://github.com/MBaysanLab/GenomicPipeline"
%}

{% endcapture %}

{% include cols.html col1=col1 %}

## Abstract

The importance of Next Generation Sequencing (NGS) rises in cancer research as accessing this key technology becomes easier for researchers. NGS analysis pipelines include several steps with different algorithms with various approaches. Benchmarking these algorithms is crucial for better utilization of the technology. In this study, we compared the performance of twelve pipelines (three mapping and four variant discovery algorithms) with recommended settings to capture single nucleotide variants. We observed significant discrepancy in variant calls among tested pipelines for different heterogeneity levels with overall high specificity and low sensitivity. Additional to the individual evaluation of pipelines, we also constructed and tested the performance of pipeline combinations and observed that certain pipelines complements each other better and display superior performance.

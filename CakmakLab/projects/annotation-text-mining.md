---
---

# Automatic Inference of Gene/Protein Annotations from Literature through Text Mining

Genes and proteins are frequently annotated with the Gene Ontology (GO) concepts. The most reliable GO annotations of genes and gene products are created by biologists manually reading related papers and determining the proper GO concepts to be assigned to the corresponding genes. Nevertheless, locating and curating information about a genomic entity from the biomedical literature requires vast amounts of human effort. In this research, we developed automated text mining tools (Cakmak and Ozsoyoglu, 2008b; Cakmak and Ozsoyoglu, 2007b; Ratprasartporn et al., 2009) to annotate genes and gene products with the Gene Ontology concepts via capturing the related knowledge embedded in textual data to expedite and automate the annotation of genomic entities by GO concepts. The proposed algorithm has reached 78% precision and 61% recall.

{% capture col1 %}

{%
  include figure.html
  image="images/cakmaklab_project/annotation-text-mining.jpg"
%}

{% endcapture %}

{% include cols.html col1=col1 %}
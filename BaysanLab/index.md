---
title: Baysan Lab
description: Current Baysan Lab Projects in the Bioinformatics Research Group
permalink: /BaysanLab/
nav:
  order: 2
  tooltip: Current Research
  main: 1
---

# Baysan Lab

*Welcome to the Baysan Lab at Istanbul Technical University!*

The Baysan Lab consists of researchers with different scientifical backgrounds and academic levels. Our laboratory mainly focuses on bioinformatics, next generation sequencing (NGS) analysis and its application on diseases such as cancer. Specifically, our efforts are dedicated to compare and integrate the NGS tools into our developed comprehensive tool [CoSAP](https://github.com/MBaysanLab/cosap), annotate the genetic variants with using public datasets and understand the genetic variants involved in the formation and course of common diseases such as cancer.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Highlights

{% capture text %}

There are many projects carried out by our lab together. One of the prominent projects is the Comparative Sequencing Analysis Platform (CoSAP). CoSAP is an easy yet comprehensive pipeline creation tool for NGS data. It provides reproducibility and aims to give deeper insight about the powers and limitations of the current tools by allowing users to compare results of different pipelines.

{%
  include button.html
  link="BaysanLab/projects"
  text="More About Projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/project3_bl.png"
  link="BaysanLab/projects"
  title="Projects"
  text=text
%}

{% capture text %}

Our up-to-date articles from members of Baysan Lab are shown in this section. You can access our article list in chronologic order from the link below.

{%
  include button.html
  link="BaysanLab/publications"
  text="More About Publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/article1.jpg"
  link="BaysanLab/publications"
  title="Publications"
  text=text
%}

{% capture text %}

Our posters are mainly related with Next Generation Sequencing (NGS) pipeline optimizations and cancer genomics studies.

{%
  include button.html
  link="BaysanLab/posters"
  text="More About Posters"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/first-project.png"
  link="BaysanLab/posters"
  title="Posters"
  text=text
%}

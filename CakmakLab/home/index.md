---
title: Home
description: Home Page of Cakmak Lab
permalink: /CakmakLab/
nav:
  order: 1
  tooltip: Main Page of Cakmak Lab
  CL: 1
---

# Çakmak Lab

Our group focuses on mining, computational analysis, and management of data in different fields with a special focus on biological and health data. Hence, our research is mostly interdisciplinary spanning diverse fields including algorithm development, systems biology, medical informatics, and databases. In particular, we develop methods and tools to study high throuhput biological and clinical datasets with the broader goal of understading diseases with their underlying mechanisms. To this end, we employ and develop techniques from data science and machine learning to create models for personalized medicine applications.

## Highlights

{% capture text %}

Check out the exciting research projects that our lab members have been working on!

{%
  include button.html
  link="CakmakLab/projects"
  text="More About Projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/cakmaklab_project/multi-omics-1.png"
  link="CakmakLab/projects"
  title="Projects"
  text=text
%}

{% capture text %}

Our up-to-date articles from members of Cakmak Lab are shown in this section. You can access our article list in chronologic order from the link below.

{%
  include button.html
  link="CakmakLab/publications"
  text="More About Publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/cakmaklab_project/publications.png"
  link="CakmakLab/publications"
  title="Publications"
  text=text
%}

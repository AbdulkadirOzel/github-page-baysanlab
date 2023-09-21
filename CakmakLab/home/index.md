---
title: Home
description: Home Page of Cakmak Lab
permalink: /CakmakLab/
nav:
  order: 1
  tooltip: Main Page of Cakmak Lab
  CL: 1
---

Cakmak Lab home page

## Highlights

{% capture text %}

There are many projects carried out by our lab together.....

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
  image="images/project3_bl.png"
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
  image="images/article1.jpg"
  link="CakmakLab/publications"
  title="Publications"
  text=text
%}

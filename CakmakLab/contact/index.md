---
title: Contact
nav:
  order: 8
  tooltip: Email, address, and location
  CL: 1
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Cakmak Lab is part of Faculty of Computer And Informatics Engineering at Istanbul Technical University. Don't hesitate to contact us through any of the provided information. We will get back to you as soon as possible.

**Bioinformatics and Databases Lab Adress:**

İTÜ Ayazağa Campus, School of Computer and Informatics, EEB 5109, 34467 Sarıyer, Istanbul.

{%
  include button.html
  type="email"
  text="Bioinformatic Research Group"
  link="bioinformatics@itu.edu.tr"
%}
{%
  include button.html
  type="email"
  text="Çakmak Lab"
  link="ali.cakmak@itu.edu.tr"
%}
{%
  include button.html
  type="address"
  text="Google Maps"
  tooltip="Our location on Google Maps at ITU"
  link="https://goo.gl/maps/LSHJ3zbvkp97XWBA6"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/lab-image.jpg"
  caption="ITU Bioinformatics Lab"
  height="315px"
  width="315px"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/faculty.jpg"
  caption="Computer & Informatics Faculty"
%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/itu.jpg"
  caption="Istanbul Technical University"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

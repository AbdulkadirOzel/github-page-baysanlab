---
---

# Predicting Future Covid-19 Mutations 

Covid-19 continues to spread over the world steadily as opposed to many earlier estimations that it would disappear in less than two years on its emergence. Even though Covid-19 vaccines have reduced the speed of the infection significantly, they could not fully stop it. On the contrary, the World Health Organization has recently published cautionary statements that infection counts are on the rise, and a huge wave is expected in winter 2022. Vaccines mostly target specific regions of the virus. The high mutation rate of Covid-19 is one essential tool that the virus exploits to escape from the available vaccines. Therefore, researchers have been working on designing next-generation vaccines against the new variants of the virus. Nevertheless, Covid-19 acquires new mutations faster than we can adapt our vaccines due to long clinical trial periods. Hence, there is a need for computational tools that can predict future Covid-19 mutations before they even emerge. In this project, we develop several deep-learning-based methods to estimate the possible future mutations in Covid-19 genome. We design and evaluate various ensemble and bagging architectures enriched with a large set of genomic, biochemical, and phylogenetic features. We evaluate our models on the GISAID data and demonstrate that the best-performing methods achieve an F1 score of 0.72. (Cakmak et al. 2022).

{% capture col1 %}

{%
  include figure.html
  image="images/cakmaklab_project/predicting-covid19.svg"
%}

{% endcapture %}

{% include cols.html col1=col1 %}
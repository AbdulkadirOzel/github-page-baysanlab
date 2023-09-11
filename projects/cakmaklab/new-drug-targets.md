---
---

# Computational Discovery of New Drug Targets

The main purpose of this research is to develop a metabolism-based pipeline that will allow computational exploration of new possible drug targets for diseases. The above-outlined approach may be adapted here with small changes. More specifically, for each reaction which is not targeted by any drug in the database, we will compute new metabolic profiles for patients after inactivating that reaction. Subsequently, the machine learning model previously created and recorded for this disease in the classification model database is applied to these new metabolic profiles. If the proportion of patients who are classified as “healthy” with their new metabolic profiles is above a certain threshold value, the proteins catalyzing the reaction and the genes encoding these proteins may be recommended as possible new drug targets.

{% capture col1 %}

{%
  include figure.html
  image="images/cakmaklab_project/new-drug-target.svg"
%}

{% endcapture %}

{% include cols.html col1=col1 %}
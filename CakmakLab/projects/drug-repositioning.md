---
---

# Drup Repositioning

The main aim of this project is to develop a metabolism-based pipeline that will allow a computational investigation of whether the currently approved drugs for any disease are suitable for use in treating diseases other than their intended target. In summary, this project involves the following parts for each disease of interest.

- Simulating the effect of each drug on patient metabolism: Each targeted enzyme by a drug would be inactivated, and the effect of these inactivations will be computationally simulated to obtain new metabolic profiles for patients.

- Employing machine learning models to assess the new profiles: Subsequently, the classification model previously created and recorded for this disease in the classification model database will be applied to these new metabolic profiles calculated in the above step. If the proportion of patients who are classified as “healthy” with the new metabolic profiles is above a certain threshold, then the drug may be recommended for repositioning for this disease. The threshold value may be determined according to the average effectiveness rate of the approved drugs.

- Exploring Combination Therapies: For some diseases, combinations of drugs are used as the main therapy. We will also computationally explore combination therapy options by unifying the targets of combined drugs into a single set, and then employ a similar approach as outlined above.

{% capture col1 %}

{%
  include figure.html
  image="images/cakmaklab_project/drug-repo.png"
%}

{% endcapture %}

{% include cols.html col1=col1 %}
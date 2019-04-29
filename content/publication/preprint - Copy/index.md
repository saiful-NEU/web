---
abstract: Under current policy decision making paradigm, we make or evaluate a policy decision by intervening different socio-economic parameters and analyzing the impact of those interventions. This process involves identifying the causal relation between interventions and outcomes. Matching method is one of the popular techniques to identify such causal relations. However, in one-to-one matching, when a treatment or control unit has multiple pair assignment options with similar match quality, different matching algorithms often assign different pairs. Since, all the matching algorithms assign pair without considering the outcomes, it is possible that with same data and same hypothesis, different experimenters can make different conclusions. This problem becomes more prominent in case of large-scale observational studies. Recently, a robust approach is proposed to tackle the uncertainty which uses discrete optimization techniques to explore all possible assignments. Though optimization techniques are very efficient in its own way, they are not scalable to big data. In this work, we consider causal inference testing with binary outcomes and propose computationally efficient algorithms that are scalable to large-scale observational studies. By leveraging the structure of the optimization model, we propose a robustness condition which further reduces the computational burden. We validate the efficiency of the proposed algorithms by testing the causal relation between Hospital Readmission Reduction Program (HRRP) and readmission to different hospital (non-index readmission) on the State of California Patient Discharge Database from 2010 to 2014. Our result shows that HRRP has a causal relation with the increase in non-index readmission and the proposed algorithms proved to be highly scalable in testing causal relations from large-scale observational studies.
authors:
- admin
- Md Sarowar Morshed
- Gary J Young
- Md Noor-E-Alam
date: "2019-04-03"
doi: ""
featured: true
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
projects: []
publication: ""
publication_short: ""
publication_types:
- "3"
slides: ""
summary: We developed a causal inference test for large-scale observational studies with binay outcomes which is robust to the choice of matching methods. We validate the efficiency of the proposed algorithms by testing the causal relation between Hospital Readmission Reduction Program (HRRP) and readmission to different hospital (non-index readmission) on the State of California Patient Discharge Database from 2010 to 2014. Our result shows that HRRP has a causal relation with the increase in non-index readmission and the proposed algorithms proved to be highly scalable in testing causal relations from large-scale observational studies.
tags:

title: Robust policy evaluation from large-scale observational studies
url_code: ""
url_dataset: ""
url_pdf: https://arxiv.org/pdf/1904.02190.pdf
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---

{{% alert note %}}
Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
{{% /alert %}}

---
layout: inner
title: Project Proposal
permalink: /about/proposal

---

### Project Proposal

**Extracting industrial strategies of clinical trials.**<br>

**Purpose**: Analyzing the clinical trial dataset to gain an understanding of the strategies of major pharmaceutical companies on new drug or intervention developments. <br>

<br>

<img src="../img/posts/image-20191104110650497.png" alt="image-20191104110650497" style="zoom:50%;" />

[Figure 1] Stakeholders of Clinical Trials <br>

**Background**: As Shown in [figure 1], Clinical trials involve many stakeholders from pharmaceutical companies to candidate participants. From an industrial perspective, a new product such as a drug or device can strengthen the company’s sales. As more advanced technologies get involved in the product development process, different strategies or collaborators are engaged for faster and efficient operation.

Starting from evaluating the change of strategies of different characteristics of companies investing in clinical trials, the project proposes to expand the analysis to concerns of more stakeholders. <br>

<br>

<img src="../img/posts/image-20191104121538956.png" alt="image-20191104121538956" style="zoom:50%;" />



<br>

**Analysis Tools**: If provided, it is useful to utilize existing tools for faster analysis. There are multiple publications on analyzing clinical trial data with tools.

(1)EXACT from BioNLP of Univ. Massachusetts.

<br>

**Datasets**: <br>

(1) Clinical trials - download xml : [clinicaltrials.gov](clinicaltrials.gov)
As shown in [figure 3], there are over 320, 846 trial records in clinicaltrials.gov.

<img src="../img/posts/image-20191104111952955.png" alt="image-20191104111952955" style="zoom:50%;" />

(2) Pharmaceutical companies - require crawling : [https://en.wikipedia.org/wiki/List_of_largest_biotechnology_and_pharmaceutical_companies](https://en.wikipedia.org/wiki/List_of_largest_biotechnology_and_pharmaceutical_companies)

<img src="../img/posts/image-20191104113216529.png" alt="image-20191104113216529" style="zoom:50%;" />

(3) MeSH API -require API calls to retreive information of MeSH Terms(Condition, Product Names) : [https://id.nlm.nih.gov/mesh/swagger/ui#/lookup/lookupTerms](https://id.nlm.nih.gov/mesh/swagger/ui#/lookup/lookupTerms) <br>

3.1) API GET "https://id.nlm.nih.gov/mesh/lookup/descriptor?label=multiple%20myeloma&match=exact&limit=10 <br>

3.2) Craw [https://id.nlm.nih.gov/mesh/D009101.html](https://id.nlm.nih.gov/mesh/D009101.html) for information



<br>

<br>

[1st Plot](../resource/data_exploration.html)  : Data exploration and find companies with the highest number of clinical trials <br>

[2nd Plot](../resource/data_exploration_type_PCA.html) : Data exploration and clustering(grouping) companies based on the frequency of type of interventions(drug, device, biological, and more)



**Additional References**:

[1] Fanshawe, Thomas R., and Rafael Perera. "Automatic extraction of quantitative data from ClinicalTrials. gov to conduct meta-analyses." *BMJ evidence-based medicine*(2019): bmjebm-2019. <br>

[2] Hao, Tianyong, et al. "Clustering clinical trials with similar eligibility criteria features." *Journal of biomedical informatics*52 (2014): 112-120.
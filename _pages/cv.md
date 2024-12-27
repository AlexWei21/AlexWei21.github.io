---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Computational Biology and Quantitative Genetics, Harvard T.H. Chan School of Public Health, 2023
* B.S. in Computer Science, Wake Forest University, 2021
* B.S. in Biology, Wake Forest University, 2021

Work experience
======
* Fall 2022 - Present: Graduate Research Assistant -> Research Associate 
  * Harvard Medical School
  * Type: Graduate Student -> Full-time
  * Duties includes:
    * Designed a novel LLM-agent-based antibiotic discovery pipeline incorporating inhibition prediction models, pharmacokinetics property prediction models, molecule generation models, and a   molecular optimization algorithm to identify molecules with high antibiotic potential against Mycobacterium tuberculosis (M.tb).
    * Benchmarked state-of-the-art molecule property prediction models including Graph Neural Networks, Equivariant Neural Networks, and Transformers on M.tb inhibition prediction and constructed a conditional Equivariant Diffusion Generative model for generating M.tb inhibitory molecules.
  * Supervisor: Maha R. Farhat

* Fall 2024 - Present: Research Associate
  * Harvard Pilgrim Health Inc.
  * Type: Part-time
  * Duties included:
    * Constructed a conditional logistic regression model and an XGBoost model to predict hospitalization-onset infection risk using Electronic Health Record (EHR) data from Mass General Brigham.
    * Investigated the impact of hospital environmental factors, including colonization pressure and prior antibiotic exposure, on the risk of hospitalization-onset infections for 12 drug-susceptible and drug-resistant organisms.
  * Supervisor: Sanjat Kanjilal

* Fall 2023 - Fall 2024: Research Associate
  * Harvard Business School
  * Type: Part-time
  * Duties included:
    * Developed a novel early-stage pandemic forecasting model that integrates deep learning with traditional compartmental models, leveraging historical pandemic data to achieve state-of-the-art performance in early-stage forecasting tasks.
    * Created a comprehensive meta-dataset of past pandemic outbreaks, including time series case data for COVID-19, Ebola, SARS, Dengue Fever, Monkeypox, Influenza, Zika Virus, and Chikungunya. This dataset supports future research in areas such as pandemic comparison and transfer learning for pandemic forecasting.
  * Supervisor: Michael Lingzhi Li

* Summer 2015: Machine Learning Summer Intern
  * Philips Healthcare North America
  * Duties included:
    * Established the first joint evaluation pipeline for pairwise Clinical Decision Support (CDS) algorithm comparison at Philips CDS Team including cohort definition, model inputs extraction, model training, and model co-performance evaluation, enabled the pairwise comparison between any two CDS algorithm that has been published or will be published in Philips on EHR data.
  
Skills
======
* Machine Learning / Deep Learning Modeling
* Drug Discovery
* Biomedical Informatics
* Clinical Research
* System Biology
* Major Programming Languages - Python, C++, R, SQL

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


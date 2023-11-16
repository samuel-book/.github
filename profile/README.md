# SAMueL-book

This page gathers the stroke modelling work for the Stroke Audit Machine Learning (SAMueL) project.

An overview of the project and a list of related publications are available on [the NIHR website](https://arc-swp.nihr.ac.uk/research/projects/samuel/).


## Summary of SAMueL-1


<details open>
<summary>[Click here] <b>What problem are we addressing?</b></summary>
<img src="https://raw.githubusercontent.com/samuel-book/.github/main/images/Slide1.JPG" alt="Summary slide 1">
</details>

<details>
<summary>[Click here] <b>What did we do?</b></summary>
<img src="https://raw.githubusercontent.com/samuel-book/.github/main/images/Slide2.JPG" alt="Summary slide 2">
</details>

<details>
<summary>[Click here] <b>What did we find?</b></summary>
<img src="https://raw.githubusercontent.com/samuel-book/.github/main/images/Slide3.JPG" alt="Summary slide 3">
</details>

<details>
<summary>[Click here] <b>What did doctors think?</b></summary>
<img src="https://raw.githubusercontent.com/samuel-book/.github/main/images/Slide4.JPG" alt="Summary slide 4">
</details>


<a href="https://samuel-book.github.io/samuel-1/introduction/intro.html"><img align="right" src="https://raw.githubusercontent.com/samuel-book/.github/main/images/online_books_400w.png" alt="Screenshots of the online books' front pages"></a>

## Online books

Our key results are published on these online books:

+ [![Jupyter Book Badge][jupyterbooks-img]][samuel1-book-link] [SAMueL-1 project][samuel1-book-link] (complete)
+ [![Jupyter Book Badge][jupyterbooks-img]][samuel2-book-link] [SAMueL-2 project][samuel2-book-link] (ongoing)

These books cover the whole process of finding our results. They contain both plain-English summaries and more technical walkthroughs. 

The contents include background information on stroke and treatment, introductions to the methods and concepts used, and applications of the methods to our data.


## Related GitHub organisations

Some of the SAMueL-2 work is also shared between other projects, and some code will be packaged up and stored elsewhere. The following organisations will store that content when it is ready:

| | | |
| --- | --- | --- |
| <a href="https://github.com/stroke-modelling/"><img src="https://avatars.githubusercontent.com/u/141143213" alt="Stroke-Modelling organisation logo" height="30"></a> [stroke-modelling][github-link-stroke-modelling] | [![GitHub Badge][github-img]][github-link-stroke-modelling] | Python packages for easily using our models. | 
| <a href="https://github.com/stroke-optimist/"><img src="https://avatars.githubusercontent.com/u/77266176" alt="OPTIMIST organisation logo" height="30"></a> [stroke-optimist][github-link-stroke-optimist] | [![GitHub Badge][github-img]][github-link-stroke-optimist]  | Stroke OPTIMIST Project: OPTimising IMplementation of Ischaemic Stroke Thrombectomy. | 
| <a href="https://github.com/stroke-digital-twin/"><img src="https://avatars.githubusercontent.com/u/145005029" alt="Stroke-Digital-Twin organisation logo" height="30"></a> [stroke-digital-twin][github-link-stroke-digital-twin] | [![GitHub Badge][github-img]][github-link-stroke-digital-twin] | Digital twins of the stroke pathway. | 

## Repositories here 

As of November 2023, the public repositories here are the following:

List of tags: `💻 Modelling` `🧮 Data prep.` `📜 Paper` `🖼️ Slides` `🍃 Overleaf` `🎮 Streamlit app` `📎 Admin` `🕮 Online book` `🧪 Test` 

<details>
<summary>[Click here] Repository list</summary>

| Repository | Description | Tags |
| --- | --- | --- |
| samuel_2_production | Core code for SAMueL-2 | `💻 Modelling` |
| ssnap_production_code | Code for running of SAMueL analysis by SSNAP | `💻 Modelling` |
| stroke_outcome_xgb_shap | XGB model, with SHAP, for stroke outcome | `💻 Modelling` |
| skeleton-pathway-model | Skeleton SimPy stroke pathway model from onset to thrombolysis and thrombectomy | `💻 Modelling` |
| stroke_outcome | Outcome modelling | `💻 Modelling` |
| samuel_causal | Causal analysis and diagrams for the SAMueL project | `💻 Modelling` |
| synthetic_data | Create synthetic data from SAMueL data | `💻 Modelling` |
| model_comparison | A comparison of different model types using SAMueL-1 data  | `💻 Modelling` |
| stroke_unit_demographics | Collating demographic data for emergency stroke unit catchment areas | `🧮 Data prep.` |
| samuel_2_data_prep | SAMUeL_2 data preparation | `🧮 Data prep.` |
| overleaf_stroke_outcome_1 | Open paper on stroke outcome modelling | `🍃 Overleaf`<br>`📜 Paper` | 
| overleaf_samuel_shap_presentation | SHAP presentation | `🍃 Overleaf`<br>`🖼️ Slides` |
| overleaf_shap_paper_2 | SHAP paper focusing on interactions | `🍃 Overleaf`<br>`📜 Paper` | 
| overleaf_shap_paper_1_for_esj | Overleaf_SHAP_paper_1_for_ESJ | `🍃 Overleaf` <br>`📜 Paper` | 
| overleaf_shap_paper_1_short | Overleaf SAMueL SHAP Paper 2 | `🍃 Overleaf`<br>`📜 Paper` | 
| overleaf_samuel_1_contentious_patients | Paper | `🍃 Overleaf`<br>`📜 Paper` | 
| overleaf_shap_pci_jan_2023 | Patient and carers meeting Jan 2023 | `🍃 Overleaf`<br>`🖼️ Slides` |
| overleaf_shap_paper_1_long | Shap paper 1 - long - preprint | `🍃 Overleaf`<br>`📜 Paper` | 
| overleaf_stakeholder_cambridge_icb_dec_2022 | Presentation to the Cambridge and Peterborough Integrated Care Board (Health Inequalities) | `🍃 Overleaf`<br>`🖼️ Slides` |
| overleaf_advisory_group_nov_2022 | SAMueL Advisory Group November 2022 | `🍃 Overleaf`<br>`🖼️ Slides` |
| overleaf_samuel_overview | Overleaf beamer slides for an overview of SAMueL, originally made for an HSMA talk in November 2022. | `🍃 Overleaf`<br>`🖼️ Slides` |
| overleaf_coproduction_workshop_1 | Coproduction workshop slides | `🍃 Overleaf`<br>`🖼️ Slides` |
| overleaf_samuel_pci_oct_2022 | pci slides | `🍃 Overleaf`<br>`🖼️ Slides` |
| samuel_shap_paper_2 | Continuing exploratory work with Shap using SAMueL-1 data | `📜 Paper` | 
| samuel_shap_paper_1 | Exploratory work with Shap using SAMueL-1 data | `📜 Paper` | 
| streamlit_combo_stroke | Combined the existing stroke streamlit apps into one multipage app | `🎮 Streamlit app` |
| streamlit_pathway_improvement | Streamlit app for pathway improvement data |  `🎮 Streamlit app` |
| streamlit_stroke_treatment_ml | Streamlit app for machine learning model to predict treatment given to emergency stroke patients |  `🎮 Streamlit app` |
| streamlit_descriptive_stats | Streamlit app for descriptive statistics for each stroke team in the SAMuEL project |  `🎮 Streamlit app` |
| streamlit_map_lsoa_outcomes | Test app for maps in streamlit | `🎮 Streamlit app`<br>`🧪 Test` |
| stroke_outcome_app | Streamlit app for stroke outcome modelling | `🎮 Streamlit app` |
| samuel-2-reference | A repository of general reference documents for the SAMueL-2 project | `📎 Admin` |
| samuel-1 | (blank)  | `🕮 Online book` |
| samuel-2 | Jupyter book for SAMueL-2 project | `🕮 Online book` |
| .github | For this organisation's README etc. | `📎 Admin` |
| causal_inference_basics | Basics of causal inference | `🧪 Test` |
| smote-variation | Variation of SMOTE | `🧪 Test` |
| import_from_relative_path | Demo to show how to import a module from a package in a different directory | `🧪 Test` |

</details>

[jupyterbooks-img]: https://jupyterbook.org/badge.svg
[samuel1-book-link]: https://samuel-book.github.io/samuel-1/introduction/intro.html
[samuel2-book-link]: https://samuel-book.github.io/samuel-2/introduction/intro.html

[github-img]: https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white
[github-link-stroke-modelling]: https://github.com/stroke-modelling/
[github-link-stroke-optimist]: https://github.com/stroke-optimist/
[github-link-stroke-digital-twin]: https://github.com/stroke-digital-twin/

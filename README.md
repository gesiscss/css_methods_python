# Introduction to Computational Social Science methods with Python

This repository contains a full introductory course to CSS methods with Python. Teaching materials meet the criteria of a gradable university course, are fully online, self-explanatory, and freely available: the materials combine coding tutorials with recommended readings, specific teaching lessons, and experience-based guidelines; they are housed, here, in a public GitHub repository, which means, everybody can study them; they have the form of Jupyter Notebooks, which means, they have the look and feel of a manuscript, yet, they contain Python code that is fully executable in a browser window, potentially without the need to locally install Python; and they are available under a Creative Commons license which allows you to freely share and adapt them. The course consists of sessions that gradually lead participants to acquire more skills in Python.

## Syllabus

The course consists of four sections. The first section teaches how to set up a computing infrastructure and conveys basic data management and scientific computing skills. The second section teaches students how to collect data using dedicated Python packages for using Application Programming Interfaces (APIs) and web scraping. The third section focuses on data preprocessing methods from network analysis and NLP and includes applications of Large Language Models (LLMs). The fourth section is about data analysis methods and goes into depth with network analysis and modeling, unsupervised and supervised ML, as well as topic modeling. Some datasets are repeatedly used throughout the course, among them a corpus of tweets on the topic of COVID (TweetsCOV19) from May 2020, social networks from the Copenhagen Networks Study (CNS), and the Varieties of Democracy (V-Dem) dataset on countries and principles of democracy. Whenever possible, sessions are interlinked and built on top of each other.

Read the syllabus [here](css_methods_python_syllabus.pdf).

## Execution

<img src="https://github.com/gesiscss/css_methods_python/blob/main/a_introduction/images/anaconda_distribution.png" height="100" align="right"></a>
Notebooks are developed for the Anaconda distribution 2022.10 which can be downloaded [here](https://repo.anaconda.com/archive/). For a complete guide how to set up your computing infrastructure and execute the course materials locally or in the cloud, please consult [Session A1: Computing infrastructure](a_introduction/1_computing_infrastructure.ipynb). Or click on this button and execute the materials in the Binder cloud:

[![Binder](https://mybinder.org/badge_logo.svg)](https://notebooks.gesis.org/binder/v2/gh/gesiscss/css_methods_python/HEAD)

## Course structure

**Section A**: [Introduction](a_introduction/)
- Session 1: [Computing infrastructure](a_introduction/1_computing_infrastructure.ipynb) (Ready for testing)
- Session 2: [Data management and relational databases](a_introduction/2_data_management_and_relational_databases.ipynb) (Ready for testing)
- Session 3: [Scientific computing and data visualization](a_introduction/3_scientific_computing_and_data_visualization.ipynb) (Ready for testing)

**Section B**: [Data collection methods](b_data_collection_methods/)
- Session 1: [API harvesting](b_data_collection_methods/1_api_harvesting.ipynb)
- Session 2: [Data parsing and static web scraping](b_data_collection_methods/2_data_parsing_and_static_web_scraping.ipynb)
- Session 3: [Dynamic web scraping](b_data_collection_methods/3_dynamic_web_scraping.ipynb)

**Section C**: [Data preprocessing methods](c_data_preprocessing_methods/)
- Session 1: [Network construction and visualization](c_data_preprocessing_methods/1_network_construction_and_visualization.ipynb) (Ready for testing)
- Session 2: [Multilayer and multimodal network construction](c_data_preprocessing_methods/2_multilayer_and_multimodal_network_construction.ipynb) (Ready for testing)
- Session 3: [Natural Language Processing](c_data_preprocessing_methods/3_natural_language_processing.ipynb) (Ready for testing)

**Section D**: [Data analysis methods](d_data_analysis_methods/)
- Session 1: [Micro-level network analysis and community detection](d_data_analysis_methods/1_micro_level_network_analysis_and_community_detection.ipynb) (Ready for testing)
- Session 2: [Macro-level network analysis and network modeling](d_data_analysis_methods/2_macro_level_network_analysis_and_network_modeling.ipynb) (Ready for testing)
- Session 3: [Unsupervised machine learning](d_data_analysis_methods/3_unsupervised_machine_learning.ipynb)
- Session 4: [Topic modeling](d_data_analysis_methods/4_topic_modeling.ipynb) (Ready for testing)
- Session 5: [Supervised machine learning](d_data_analysis_methods/5_supervised_machine_learning.ipynb)

## Acknowledgement

These resources have been developed as part of the [Social ComQuant](https://socialcomquant.ku.edu.tr/) project which had been funded as a twinning project among Koç University (Istanbul, Turkey), GESIS – Leibniz Institute for the Social Sciences (Cologne, Germany), and the ISI Foundation (Torino, Italy) under the European Commission's Horizon 2020 funding line.

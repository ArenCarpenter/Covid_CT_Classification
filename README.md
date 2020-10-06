# Covid19_CT_Classification (WIP)

**Aren Carpenter**

September/October 2020

Submission for Grand Challenge's 'CT Diagnosis of Covid-19' challenge. It is a binary classification problem for determining the presence of Covid-19 solely from CT scans of patients. 

## Introduction & Social Case

Few outbreaks in modern history have had as large of a public health and economic effect as Covid-19. While a vaccine is still in progress, physicians need cheap and effective techniques for identifying Covid-19 positive patients. 

As of Sept 12, 2020, there have been more than 28 million cases and 900,000 deaths related to Covid-19, including 200,000 in the United States alone. 

## Repository Navigation

* **[001_Image_Load_and_Clean.ipynb](001_Image_Load_and_Clean.ipynb)**: Loading images and creating train/validation/test sets with a 70/15/15 split
* **[002_Exploratory_Data_Analysis](002_Exploratory_Data_Analysis.ipynb)**: Exploratory Data Analysis to create visualizations, including average images, class imbalance chart, and std images
* **[003_Modeling.ipynb](003_Modeling.ipynb)**: Modeling locally with Keras framework

001 allows one to make directories and sort images according once data has been downloaded locally. 002 lets one generate EDA visualizations from local images once sorted. 003 allows for modeling locally utilizing the Keras framework and has functions for performance evaluation and tracking.

## Data and EDA

The images are collected from COVID19-related papers from medRxiv, bioRxiv, NEJM, JAMA, Lancet, etc. CTs containing COVID-19 abnormalities are selected by reading the figure captions in the papers.

The dataset contains 349 positive images from 216 patients and 463 negative images. Thus, class imbalance was not a large problem. 

The data can be found on the submission's GitHub page: https://github.com/UCSD-AI4H/COVID-CT, and the challenge entry is here: https://covid-ct.grand-challenge.org/CT-diagnosis-of-COVID-19/.

This paper describes the collection and prep steps taken by the authors of the challenge in preparation for its usage in the public sphere: https://arxiv.org/pdf/2003.13865.pdf. 

## Modeling

Following the CRISP-DM framework for developing models informed from data and social case understanding. My modeling followed an iterative approach and rigorous hypothesis testing utilizing a swath of procedures for improving model performance.

## Insights & Recommendations

## Next Steps
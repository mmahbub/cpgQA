# cpgQA

## Question Answering Dataset for Clinical Practice Guidelines

This repo contains the question-answering dataset proposed in the paper `cpgQA: A benchmark dataset for machine reading comprehension task on clinical practice guidelines and a case study using transfer learning`.

The resource used to make this dataset is a [clinical practice guideline on opioid therapy](https://www.healthquality.va.gov/guidelines/Pain/cot/VADoDOTCPG022717.pdf).

`cpgQA` has 1097 QA pairs and 190 unique contexts.

The `cpgQA` dataset resides in the `dataset` folder. The dataset is saved in both CSV (`cpgQA-v1.0.csv`) and JSON (`cpgQA-v1.0.json`) formats.

The `dataset` folder also contains the unlabeled target-domain training set (`unlabeled_train_target.json`) used for experimenting with [BioADAPT-MRC](https://academic.oup.com/bioinformatics/article/38/18/4369/6649678).

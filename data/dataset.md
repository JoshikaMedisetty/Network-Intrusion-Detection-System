# CICIDS2017 Dataset

## Overview

This project uses the **CICIDS2017** dataset developed by the **Canadian Institute for Cybersecurity (CIC)**. It is one of the most widely used benchmark datasets for evaluating Machine Learning-based Network Intrusion Detection Systems (NIDS).

## Dataset Details

- **Dataset:** CICIDS2017
- **Source:** Canadian Institute for Cybersecurity (CIC)
- **Network Flows:** Approximately 2.5 million
- **Features:** 78 network traffic features
- **Classes:** 12 traffic classes (Benign and multiple attack categories)

## Folder Structure

```text
data/
├── raw/
│   └── Original dataset files
└── processed/
    └── Cleaned and preprocessed dataset used for model training
```

## Preprocessing

The dataset was preprocessed before training the machine learning models. The preprocessing steps include:

- Handling missing and invalid values
- Removing duplicate records (if applicable)
- Feature selection
- Data cleaning
- Preparing the dataset for model training and evaluation

## Download

The original CICIDS2017 dataset can be downloaded from the official website:

https://www.unb.ca/cic/datasets/ids-2017.html

## Note

Due to GitHub file size limitations, the complete dataset may not be included in this repository. If required, download the dataset from the official source and place it in the appropriate `data/raw/` directory before running the notebook.
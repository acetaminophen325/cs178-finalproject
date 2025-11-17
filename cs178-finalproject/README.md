# CS178 Project – IMDB Sentiment Classification

## Overview

This project is for UCI CS178 (Fall 2025).  
We use the IMDB Large Movie Review Dataset to build and compare machine learning models for binary sentiment classification (positive vs. negative reviews).

## Dataset

- Dataset: IMDB Large Movie Review Dataset
- Source: Stanford / ACL IMDB
- Local path (not in Git): `data/raw/imdb/aclImdb/`

Each teammate should:

1. Download the dataset from the official source.
2. Extract the `aclImdb` folder.
3. Place it at: `data/raw/imdb/aclImdb/`

## Project Structure

```text
cs178-imdb-project/
├─ data/
│  ├─ raw/
│  │  └─ imdb/
│  │     └─ aclImdb/          # original IMDB dataset (not tracked by git)
│  └─ processed/
│     └─ imdb/                # saved tokenized/vectorized variants
├─ notebooks/
│  ├─ 01_eda.ipynb
│  ├─ 02_baselines.ipynb
│  └─ 03_extra_models.ipynb
├─ src/
│  ├─ __init__.py
│  ├─ data_loader.py
│  ├─ preprocess.py
│  ├─ models/
│  │  ├─ __init__.py
│  │  ├─ baseline.py
│  │  └─ deep.py              # optional, for NN models
│  ├─ train.py
│  └─ evaluate.py
├─ results/
│  ├─ figures/
│  └─ tables/
├─ reports/
│  └─ project_report.*
├─ .gitignore
├─ environment.yml
└─ README.md

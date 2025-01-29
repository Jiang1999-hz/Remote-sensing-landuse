# Master's Thesis: Multi-model based UMP Prediction

## Project Overview

This project aims to predict **UMP (User-Defined Metric)** using a multi-model approach. By integrating various machine learning models, the goal is to enhance prediction accuracy and robustness.

## Repository Structure

- `data/`: Contains datasets, both raw and processed.
- `src/`: Source code for data preprocessing, model training, evaluation, and utilities.
- `notebooks/`: Jupyter Notebooks for data exploration, model building, and results visualization.
- `experiments/`: Configuration and results of different experiments for easy tracking.
- `tests/`: Unit tests to ensure code reliability.
- `docs/`: Project documentation, including thesis drafts and references.
- `scripts/`: Automation scripts for common tasks.
- `references/`: Relevant literature and materials.

## Installation and Setup

### Environment Setup

It is recommended to use Python 3.8 or higher. You can create a virtual environment using `venv` or `conda`.

```bash
# Using venv
python3 -m venv env
source env/bin/activate

# Using conda
conda create -n ump-prediction python=3.8
conda activate ump-prediction

Remote-sensing-landuse/
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
├── data/
│   ├── raw/
│   ├── processed/
│   └── README.md
├── src/
│   ├── __init__.py
│   ├── data_preprocessing.py
│   ├── model_training.py
│   ├── model_evaluation.py
│   └── utils.py
├── notebooks/
│   ├── data_exploration.ipynb
│   ├── model_building.ipynb
│   └── results_visualization.ipynb
├── experiments/
│   ├── experiment_1/
│   │   ├── config.yaml
│   │   └── results/
│   └── experiment_2/
│       ├── config.yaml
│       └── results/
├── tests/
│   ├── test_data_preprocessing.py
│   ├── test_model_training.py
│   └── test_model_evaluation.py
├── docs/
│   ├── thesis/
│   │   ├── chapters/
│   │   │   ├── introduction.md
│   │   │   ├── methodology.md
│   │   │   ├── results.md
│   │   │   └── conclusion.md
│   │   └── references.bib
│   └── README.md
├── scripts/
│   ├── run_preprocessing.sh
│   ├── run_training.sh
│   └── run_evaluation.sh
└── references/
    └── related_work.pdf

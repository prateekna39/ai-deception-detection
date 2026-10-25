@"
# AI-Based Deception Detection System

A machine learning project exploring truth-versus-deception classification using structured behavioral annotations from the DOLOS dataset.

## Project structure

- notebooks/: Jupyter notebook for data inspection, preprocessing, training, and evaluation.
- preprocessing/: Reusable preprocessing code.
- models/: Model code and optional saved model artifacts.
- results/metrics/: Evaluation metrics and classification report.
- data/DOLOS/: Local dataset; not included in this repository.

## Setup

1. Clone this repository.
2. Install Python 3.10 or newer.
3. Run: pip install -r requirements.txt
4. Obtain authorized access to DOLOS.
5. Place the dataset in data/DOLOS/ and protocol files in data/DOLOS/Training_Protocols/.
6. Open notebooks/milestone_2.ipynb and run cells in order.

## Baseline

Model: Random Forest Classifier
Features: 43 structured behavioral features
Trees: 200
Preliminary accuracy: 54.48%
Preliminary F1-score: 59.24%

These are preliminary experimental results, not validated real-world lie-detection performance.

## Dataset access

The dataset is excluded from this repository. Each team member must obtain an authorized copy. Do not redistribute it unless its terms explicitly permit sharing.
"@ | Set-Content README.md
# Network Intrusion Detection with Machine Learning

This project explores the use of Machine Learning techniques for network intrusion detection using the CIC-IDS-2017 dataset.

## Current stage

The project currently includes two main experiments:

- binary classification between BENIGN and DDoS traffic;
- multiclass classification between BENIGN traffic and multiple attack categories.

The first notebook focuses on a simpler binary problem using a single CIC-IDS-2017 CSV file. The second notebook combines multiple CSV files and trains a multiclass model to distinguish between different types of network traffic and attacks.

## Notebooks

- `01_binary_ddos_detection.ipynb`: trains and evaluates binary classification models to distinguish BENIGN traffic from DDoS traffic.
- `02_multiclass_attack_classification.ipynb`: combines multiple CSV files, preprocesses the data, trains a multiclass Random Forest model and evaluates its performance using weighted and macro metrics, a classification report and a confusion matrix.

## Dataset

The dataset used is CIC-IDS-2017.

The CSV files are stored locally in:

```text
data/


# Molecular Generation using Reinforcement Learning

## 1. Project Overview
This project explores molecular generation using Reinforcement Learning.
The goal is to generate molecular structures represented as SMILES
and optimize their properties through reward-based learning.

## 2. Tech Stack
- Language: Python
- Environment: Google Colab
- Framework: PyTorch
- Chemistry Toolkit: RDKit
- Dataset: ZINC

## 3. Main Features
- SMILES-based molecular representation
- GRU-based Policy Network
- Molecular pretraining using Cross Entropy Loss
- Policy optimization using REINFORCE
- Reward Shaping for molecular property optimization
- Molecular validity and diversity evaluation

## 4. Model Training
- Pretraining Dataset: 249,455 SMILES
- Pretraining Epochs: 3
- Batch Size: 512
- Reinforcement Learning Episodes: 10,000

## 5. Evaluation Results
Evaluation was performed on 100 generated molecules.

| Metric | Result |
|---|---:|
| Validity | 100% |
| Diversity | 0.7222 |
| pLogP | 4.3787 |
| Overall Score | 0.6411 |

## 6. My Contributions
- Implemented the GRU-based Policy Network
- Developed the molecular pretraining pipeline
- Applied REINFORCE for policy optimization
- Implemented reward shaping
- Evaluated generated molecules using validity, diversity, and pLogP

## 7. Project Structure
- `*.ipynb`: Google Colab notebook containing the implementation and experiments

## 8. Notes
This project was developed as part of a university course.
Sections 0–4 are based on the professor-provided template,
while sections 5 and onward contain my implementation and extensions.

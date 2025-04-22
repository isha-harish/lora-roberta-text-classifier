# lora-roberta-text-classifier

This repository contains the code and the final report for the project **"Fine-Tuning RoBERTa with LoRA on AG News Classification"**. The project demonstrates the use of Low-Rank Adaptation (LoRA) to efficiently fine-tune a pre-trained RoBERTa model on the AG News classification task under a 1M parameter budget.

### Project Members:
- **Greeshma Hedvikar** (gh2461@nyu.edu)
- **Isha Harish** (ih2363@nyu.edu)
- **Lavanya Deole** (lnd2037@nyu.edu)

## Project Overview

This project applies **Low-Rank Adaptation (LoRA)** to fine-tune the RoBERTa model on the **AG News dataset** for text classification. The goal was to optimize a model under a strict **1M parameter budget** while achieving strong performance. We successfully fine-tuned the model with an **88.1% validation accuracy** and ranked **37th on the Kaggle private leaderboard** with an **85.275% accuracy**.

## Key Files

- **`FineTuning with LoRa.ipynb`**: The Jupyter notebook containing the full implementation of the RoBERTa fine-tuning process with LoRA. This includes data preprocessing, model setup, training, and evaluation.
  
- **`FineTuning with LoRa.pdf`**: The final report documenting the project's methodology, results, and conclusions.

## Key Features
- **Dataset**: AG News (120,000 labeled news articles in 4 categories: World, Sports, Business, Sci/Tech)
- **Model**: RoBERTa (base)
- **Techniques Used**: Low-Rank Adaptation (LoRA), AdamW optimizer, CosineLR scheduler, Mixed Precision (fp16)
- **Result**: 88.1% validation accuracy, 85.275% private Kaggle leaderboard accuracy (Rank 37)

##How to Run the Code
###1. Clone the repository

```bash
git clone https://github.com/isha-harish/lora-roberta-text-classifier.git
cd  lora-roberta-text-classifier

```

###2. Open the notebook

```bash
jupyter notebook "FineTuning with LoRa.ipynb"
```
###3. Run the cells
Follow the instructions in the notebook to:

- Load and preprocess the AG News dataset

- Fine-tune the RoBERTa model with LoRA

- Track the training process and evaluate the model performance

##Acknowledgements
Hugging Face for their transformers and datasets libraries

Weights & Biases for tracking the model's performance






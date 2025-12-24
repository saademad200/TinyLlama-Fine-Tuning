# TinyLlama Fine-Tuning: SFT + DPO

This project implements Supervised Fine-Tuning (SFT) and Direct Preference Optimization (DPO) on TinyLlama for the IBA Text Analytics Assignment.

## Project Structure

```
├── notebooks/           # Jupyter notebooks for training & evaluation
├── src/                 # Utility modules
├── configs/             # Training configuration files
├── evaluation/          # Evaluation prompts and results
└── outputs/             # Model checkpoints
```

## Setup

```bash
pip install -r requirements.txt
```

## Datasets
- **SFT**: databricks/databricks-dolly-15k
- **DPO**: argilla/distilabel-intel-orca-dpo-pairs

## Usage

1. Run `notebooks/01_data_preparation.ipynb` to prepare datasets
2. Run `notebooks/02_sft_training.ipynb` for supervised fine-tuning
3. Run `notebooks/03_dpo_training.ipynb` for preference optimization
4. Run `notebooks/04_evaluation.ipynb` for comprehensive evaluation

## Model
- **Base Model**: TinyLlama/TinyLlama-1.1B-Chat-v1.0

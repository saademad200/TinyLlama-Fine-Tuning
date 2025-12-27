# TinyLlama Fine-Tuning: SFT + DPO

This project implements Supervised Fine-Tuning (SFT) and Direct Preference Optimization (DPO) on TinyLlama for the IBA Text Analytics Assignment.

## Project Structure

```
├── notebooks/           # Jupyter notebooks for training & evaluation
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

1. Run `notebooks/tiny-llama-finetuning.ipynb` to run combined notebook

## Model
- **Base Model**: TinyLlama/TinyLlama-1.1B-Chat-v1.0

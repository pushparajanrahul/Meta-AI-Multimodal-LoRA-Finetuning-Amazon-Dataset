# Meta AI Multimodal LoRA Fine-Tuning on Amazon Product Dataset

This repository demonstrates how to fine-tune a **Meta AI multimodal model** on the **Amazon product dataset** using the **LoRA** (Low-Rank Adaptation) method to optimize various modules for vision, language, and attention tasks. The fine-tuning is performed using the **Unsloth framework**, enabling faster training with minimal memory usage.

## Objective
The objective of this project is to fine-tune a pretrained **Meta AI multimodal model** using **LoRA** on the **Amazon product dataset**. LoRA allows for efficient adaptation of large models by reducing the number of trainable parameters while maintaining high performance.

## Key Technologies
- **Meta AI**: Pretrained multimodal model
- **LoRA**: Low-Rank Adaptation method
- **Unsloth Framework**: 2x faster fine-tuning with optimized GPU usage
- **Amazon Product Dataset**: The dataset used for multimodal fine-tuning

## Impact
- **Training Loss Reduction**: Reduced training loss by **65%** (from **3.20** to **1.10**) over 30 steps.
- **Memory Efficiency**: Significant reduction in memory usage, allowing faster fine-tuning.
- **Training Speed**: Achieved **2x faster** training due to **LoRA** and **Unsloth** optimizations.

## Setup

### Requirements
- Python 3.x
- PyTorch
- Unsloth Framework
- Meta AI Pretrained Model
- LoRA Implementation

### Installation
```bash
# Clone the repository
git clone https://github.com/<your-username>/Meta-AI-Multimodal-LoRA-Finetuning-Amazon-Dataset.git

# Install required libraries
pip install -r requirements.txt

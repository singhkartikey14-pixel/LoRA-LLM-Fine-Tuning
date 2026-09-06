# LoRA LLM Fine-Tuning

A Generative AI project demonstrating parameter-efficient fine-tuning of a Large Language Model using LoRA (Low-Rank Adaptation).

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- PEFT (LoRA)
- BitsAndBytes
- Hugging Face Datasets
- Google Colab
- NVIDIA GPU

## Project Overview

This project demonstrates how LoRA can be used to fine-tune a pretrained Large Language Model without updating all of the model parameters.

LoRA reduces the number of trainable parameters, making LLM fine-tuning more memory-efficient and suitable for limited GPU resources.

## Workflow

1. Install required libraries
2. Load and preprocess the dataset
3. Load the pretrained model and tokenizer
4. Configure LoRA using PEFT
5. Fine-tune the model
6. Evaluate the trained model
7. Perform inference on new prompts

## Notebook

The complete implementation is available in:

Lora_FineTunning.ipynb

## Skills Demonstrated

Generative AI • LLM Fine-Tuning • LoRA • PEFT • Transformers • PyTorch • Model Quantization • NLP

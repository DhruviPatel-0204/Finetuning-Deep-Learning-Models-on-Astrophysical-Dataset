# Finetuning-Deep-Learning-Models-on-Astrophysical-Dataset

## Overview
This project evaluates and fine-tunes the ResNet-50 model on the GalaxyZoo dataset to classify galaxy morphologies. The process includes evaluating the pre-trained model, fine-tuning it on the training split, and further fine-tuning using LoRA (Low-Rank Adaptation) for efficient learning.

## Steps Completed
1) Evaluated Pre-trained ResNet-50 Model

    Loaded the pre-trained ResNet-50 model.
    Evaluated the model on the GalaxyZoo test split.
    Calculated performance metrics such as accuracy, precision, recall, and F1-score.

2) Fine-tuned ResNet-50 Model

    Fine-tuned the pre-trained ResNet-50 model on the train split of the GalaxyZoo dataset.
    Evaluated the fine-tuned model on the test split and compared the results with the pre-trained evaluation.

3) Fine-tuned Using LoRA

    Implemented LoRA (Low-Rank Adaptation) for efficient fine-tuning of the ResNet-50 model.
    Fine-tuned the model on the train split and evaluated it on the test split.
    Compared the LoRA-finetuned model's performance with the standard fine-tuned model.

# coling-2025-mgt-detection
This repository contains a solution for the COLING-2025 Workshop on MGT Detection Task 1. The task involves detecting machine-generated text (MGT) in English. The solution implements transformer-based models, evaluation metrics, and custom preprocessing steps to achieve high performance in binary classification of MGT.

# MGT Detection Task 1 - COLING 2025 Workshop

## Overview
This repository contains the solution developed for the COLING-2025 Workshop on MGT Detection Task 1. The task aims to detect whether a given text is machine-generated (MGT) or human-authored. The solution is implemented for two subtasks:
- **Subtask A**: English-only MGT detection.
- **Subtask B**: Multilingual MGT detection.

## Approach
Our approach utilizes transformer-based models for both English and multilingual tracks:
- **RoBERTa** for the English track.
- **XLM-R** for the multilingual track.

### Key Features:
- Preprocessing pipelines tailored for English and multilingual data.
- Transformer models fine-tuned on the provided training data.
- Evaluation metrics including macro F1-score, accuracy, and micro F1.
- Format checker and scorer scripts for verifying prediction files.
- Results tracking and model versioning.

## Running the Solution
To run the baseline model, execute the following command:



# ML-DL-
This Repo Contains all projects related to Machine Learning specifically Based on Deep Learning Algorithms.
1)
# MedSectAI - Enhancing Medical Research Paper Readability with NLP

## Description
MedSectAI is a project aimed at improving the readability and understanding of medical research papers using Natural Language Processing (NLP). This project explores multiple approaches, from baseline models to advanced deep learning architectures, and concludes with a multimodal model combining token, character, and positional embeddings. The goal is to enhance the comprehension of scientific literature, particularly in the medical field.

## Dataset
The dataset used in this project is sourced from the paper's author on GitHub: [PubMed-RCT](https://github.com/Franck-Dernoncourt/pubmed-rct). The dataset includes multiple files such as `train.txt`, `dev.txt`, and `test.txt`. These files were preprocessed to ensure they meet the model’s input requirements.
#for faster experimentation 10 or 20 percent dataset is generally used in some experiment even 10 percent of this smaller dataset is used for fitting.
# Helper functions for preparing data, creating vectorizers, and building models are defined.

## Modeling Experiments
### --- Deep Learning Models ---
### The deep learning models (Models 0-5) are trained sequentially.

### 1. Model 0: Naive Base Model
### 2. Model 1: Token-based Conv1D
### 3. Model 2: Pretrained Universal Sentence Encoder
### 4. Model 3: Character-Level Convolutional Neural Network
### 5. Model 4: Multimodal Model (Token + Character)
### 6. Model 5: Quadra Model (Token + Character + Positional Embedding(line number embedding + total lines embedding))

## For each model:
- Dataset preparation
- Architecture design
- Training and validation
- Metrics calculation and visualizationare implemented systematically.

##Results 
Here only F1 score is shown for Complete Result analysis Read the code.( ###For 20 percent Dataset)

   Model            F1 Score
1. Model 0:          0.6989
2. Model 1:          0.7855
3. Model 2:          0.7209
4. Model 3:          0.6332
5. Model 4:          0.7260
6. Model 5:          0.8610

After Training Data on complete Dataset more than 93% of F1 score can be achieved which I avoided obiviously because of computation power limitations,Training 
time Constraints and Speed Accuracy trade-offs.




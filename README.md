# Multimodal image classification
 
This project focuses on the classification of tumor images using two distinct approaches: a feed-forward neural network based on Few-Shot Learning (FSL) and the application of SNAIL (Simple Neural Attentive Meta-Learner) techniques. The goal is to accurately classify tumor images into relevant categories based on their features.

## Project Overview

- **FSL-Based Feed-Forward Network**: In the first approach, we employ Few-Shot Learning techniques to create a feed-forward neural network capable of recognizing tumor features. The network is designed to learn from a limited set of labeled examples and generalize to classify new, unseen tumor images.

- **SNAIL Technique**: In the second approach, we leverage the Simple Neural Attentive Meta-Learner (SNAIL) technique, a promising approach for few-shot learning tasks. SNAIL employs attention mechanisms to focus on relevant features and adapt to different tasks with limited training data.

## Project Structure

The project is organized as follows:

- `FSL_SimpleNN.ipynb`: Jupyter Notebook containing the code for the FSL-based feed-forward network for tumor image classification.
  
- `Final.ipynb`: Jupyter Notebook containing the code for the tumor image classification using SNAIL techniques.
  
- `Features/`: Directory containing the dataset of features extracted from tumor images and scripts.
  
- `models/`: Directory containing pre-trained models and model checkpoints.

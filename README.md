# Chest X-ray Preliminary Report Generation

This project implements a **deep learning framework** for automatic preliminary report generation from chest X-ray images. It aims to assist radiologists by providing semi-automated textual descriptions, reducing workload, and improving efficiency in clinical workflows.

## Features
- **Data Augmentation:** Includes rotation, translation, brightness adjustment, zoom, shear, horizontal flips, and random cropping to improve model generalization.
- **Feature Extraction:** Utilizes **CheXNet (DenseNet121)** to extract key image features from chest X-rays.
- **Encoder-Decoder Model:** LSTM-based text generation combines image features with text embeddings for report generation.
- **Training & Optimization:** Uses AdamW optimizer, learning rate warm-up, ReduceLROnPlateau scheduler, dropout regularization, and early stopping.
- **Evaluation:** Reports are evaluated using **BLEU scores** and visual comparisons with reference captions.
- **Visualization:** Randomly generated predictions are displayed alongside true captions for qualitative analysis.


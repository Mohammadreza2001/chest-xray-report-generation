# chest-xray-report-generation
This project builds an end-to-end pipeline for chest X-ray captioning. It uses data augmentation, CheXNet feature extraction, and a PyTorch encoder–decoder with BiLSTM to generate radiology-style reports. Training applies AdamW, scheduling, and early stopping, with BLEU-based evaluation of generated captions.

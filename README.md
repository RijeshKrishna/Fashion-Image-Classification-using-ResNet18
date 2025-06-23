# 👗 Fashion Image Classification using ResNet18

This project aims to classify fashion product images into categories using deep learning. It leverages PyTorch and a pre-trained ResNet18 model, fine-tuned on the Fashion Product Images dataset from Kaggle.

## 📦 Dataset

- Source: [Fashion Product Images (Small)](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset)
- Contains over 44,000 fashion product images with metadata including category, gender, and usage.

## 🧠 Model

- **Architecture**: ResNet18
- **Framework**: PyTorch
- **Training Strategy**:
  - Image preprocessing using `torchvision.transforms`
  - Label encoding for categories
  - Data loaded using a custom `Dataset` class
  - Fine-tuned only the final layer of ResNet18

## 📊 Results

- Accuracy: ~`xx%` (Fill after training)
- Loss: `...`
- Confusion matrix, accuracy plots available in the notebook.

## 🔧 Setup

### Requirements

```bash
pip install -r requirements.txt

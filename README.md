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

- Train Accuracy: 0.9268
- Val Accuracy: 0.8682
- Train Loss: 0.2180
- Val Loss: 0.4508

## 🔧 Setup
jupyter notebook fashion_prediction_resnet.ipynb

### Requirements
pip install kagglehub torch torchvision pandas scikit-learn matplotlib tqdm


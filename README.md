# MNIST Classification Model

A fully-connected neural network trained on the MNIST handwritten-digit dataset using PyTorch.  
This notebook demonstrates data loading, model definition, training, evaluation, and visualization of results.

---

## 🚀 Features

- **Data Loading** via `torchvision.datasets.MNIST`  
- **Reproducible Training** (fixed seeds for Python, NumPy, and PyTorch)  
- **Simple Feed-Forward Classifier** using `nn.Sequential` and `nn.Flatten`  
- **Training & Validation Loop** with loss tracking over epochs  
- **Evaluation Metrics**:  
  - Classification report (precision, recall, F1-score)  
  - Confusion matrix visualized with Seaborn  
- **Device-Agnostic**: runs on GPU if available, otherwise CPU  

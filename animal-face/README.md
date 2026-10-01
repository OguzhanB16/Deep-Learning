# 🐾 AFHQ Image Classification with Custom ResNet-18

This project features a **ResNet-18** deep learning model built from scratch using PyTorch to classify images (Cat, Dog, Wild) from the **Animal Faces HQ (AFHQ)** dataset. 

No pretrained weights were used; the core building blocks of ResNet, including the `BasicBlock` architecture, residual/shortcut connections, and custom data loading (Dataset/DataLoader) classes, were designed from the ground up.

## 🚀 Project Features

- **Custom ResNet-18 Architecture:** `BasicBlock` and Layer structures built from scratch using PyTorch `nn.Module`, staying true to the original paper.
- **Custom Dataset Class:** A custom Dataset class integrated with Pandas DataFrame, utilizing `LabelEncoder` and performing on-the-fly data normalization/augmentation (RGB conversion, 224x224 resizing) with `torchvision.transforms`.
- **Optimized Training Loop:** A robust training and validation algorithm that prevents GPU bottlenecks, employs `.item()` and `torch.no_grad()` best practices, and calculates loss and accuracy metrics at every epoch.
- **Visualization:** Comparative graphs of Model Loss and Accuracy plotted using Matplotlib after the training process.

## 🛠️ Technologies Used

- **Language:** Python
- **Deep Learning Framework:** PyTorch, Torchvision
- **Data Processing:** Pandas, Scikit-learn (`LabelEncoder`, `train_test_split`)
- **Image Processing:** PIL (Python Imaging Library)
- **Visualization:** Matplotlib

## 📁 Dataset (AFHQ)

The model is trained on the [Animal Faces-HQ (AFHQ)](https://github.com/clovaai/stargan-v2) dataset. The dataset consists of three main classes:
1. `cat`
2. `dog`
3. `wild`

## ⚙️ Installation and Usage

**1. Clone the Repository:**
git clone https://github.com/OguzhanB16/Deep-Learning.git
cd your-repo-name

**2. Install Required Libraries:**
pip install torch torchvision pandas scikit-learn matplotlib pillow

**3. Train the Model:**
To start the training process, run the training script (e.g., train.py or Jupyter Notebook). The model will automatically train on the GPU (cuda) if available, otherwise on the CPU.

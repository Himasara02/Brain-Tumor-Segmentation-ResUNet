# 🧠 Brain Tumor Segmentation using ResUNet

## 📖 Project Overview

Deep Learning-Based Medical Image Segmentation Using ResUNet architecture for accurate brain tumor segmentation from MRI images. This project was developed from May 2024 – August 2024, leveraging encoder-decoder convolutional networks with residual connections to improve segmentation precision and boundary detection.

The system was trained and evaluated on the BraTS dataset with extensive preprocessing, data augmentation, and Dice coefficient analysis for performance evaluation. The model achieved high segmentation accuracy and robust generalization across MRI modalities.

**Technologies:** Python, TensorFlow, Keras, OpenCV  
**Optimization:** Dice Loss and Adam optimizer for enhanced convergence

## 🎥 Reference Tutorial

This project is inspired by and follows concepts from:
- **YouTube Tutorial:** https://youtu.be/fimm72Nwl7U

## 📊 Dataset

The project uses the **LGG Brain MRI Segmentation** dataset from Kaggle:
- **Dataset Link:** https://www.kaggle.com/mateuszbuda/lgg-mri-segmentation
- Contains MRI scans of Lower Grade Glioma (LGG) brain tumors
- Includes both original MRI images and corresponding tumor masks

## 🏗️ ResUNet Architecture

ResUNet combines the benefits of U-Net architecture with residual connections:

- **Encoder-Decoder Structure:** Captures both local and global features
- **Residual Connections:** Helps with gradient flow and feature preservation
- **Skip Connections:** Preserves fine-grained spatial information
- **Bottleneck Design:** Efficient feature extraction with reduced parameters

**Why ResUNet for Medical Segmentation?**
- Better gradient flow through deep networks
- Improved feature preservation across scales
- Enhanced boundary detection capabilities
- Robust performance on medical imaging tasks

## ⚙️ Installation & Usage

### Prerequisites
- Python 3.7+
- CUDA-compatible GPU (recommended)

### Setup
1. Clone the repository:
```bash
git clone https://github.com/Himasara02/Brain-Tumor-Segmentation-ResUNet.git
cd Brain-Tumor-Segmentation-ResUNet
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch the Jupyter notebook:
```bash
jupyter notebook notebooks/Healthcare_AI.ipynb
```

## 🚀 Project Features

- **🏗️ ResUNet Architecture:** Encoder-decoder with residual blocks for improved segmentation
- **🎯 Advanced Loss Functions:** Focal Tversky loss and Dice loss for better boundary detection
- **🔄 Transfer Learning:** Pre-trained backbone for faster convergence
- **📈 Data Augmentation:** Comprehensive MRI-specific augmentation techniques
- **📊 Performance Metrics:** Dice coefficient, IoU, and pixel accuracy evaluation
- **🖼️ Visualization Tools:** Interactive plots for training progress and results

## 📚 Project Structure

```
Brain-Tumor-Segmentation-ResUNet/
│
├── data/                    # Dataset storage
├── models/                  # Saved models and checkpoints
├── notebooks/              # Jupyter notebooks
│   └── Healthcare_AI.ipynb # Main implementation notebook
├── requirements.txt        # Project dependencies
├── .gitignore             # Git ignore rules
└── README.md              # This file
```

## 📈 Results

*This section will be updated with model performance metrics, training curves, and segmentation examples once the model training is complete.*

### Expected Performance Metrics:
- **Dice Coefficient:** Target > 0.85
- **IoU Score:** Target > 0.80
- **Pixel Accuracy:** Target > 0.95

## 🔗 References & Credits

- **Original Tutorial:** YouTube channel providing ResUNet implementation guidance
- **Dataset:** Kaggle LGG Brain MRI Segmentation dataset
- **Architecture:** ResUNet paper and implementations
- **Medical Imaging:** BraTS challenge methodologies

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Himasara Kulasinghe**  
📧 himasara.divya@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/himasaraK/) | [GitHub](https://github.com/Himasara02)

---

⭐ If you found this project helpful, please give it a star!
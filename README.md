# ♻️ AI-Powered Smart Waste Classification

An AI-powered waste classification system that uses Deep Learning and Transfer Learning to automatically classify waste images into six categories.

## 🧠 Project Overview

This project uses a pre-trained **EfficientNetV2B0** model with transfer learning to classify waste images into six categories:

* Cardboard
* Glass
* Metal
* Paper
* Plastic
* Trash

The model uses image size **224 × 224** and includes a two-phase training process: classifier-head training followed by fine-tuning of the backbone.

## 🚀 Technologies Used

* Python
* TensorFlow / Keras
* EfficientNetV2B0
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## 📊 Waste Categories

| Category  | Description     |
| --------- | --------------- |
| Cardboard | Cardboard waste |
| Glass     | Glass waste     |
| Metal     | Metal waste     |
| Paper     | Paper waste     |
| Plastic   | Plastic waste   |
| Trash     | General waste   |

## ⚙️ Model Configuration

* Image Size: 224 × 224
* Batch Size: 32
* Backbone: EfficientNetV2B0
* Head Training Epochs: 12
* Fine-Tuning Epochs: 30
* Dropout: 0.3
* Label Smoothing: 0.1
* Confidence Threshold: 0.60

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Select **Runtime → Change runtime type → T4 GPU**.
3. Upload the required dataset ZIP when prompted.
4. Run the notebook cells sequentially.
5. Train the model and evaluate its performance.

## 📁 Repository Structure

```text
Smart-Waste-Classification/
│
├── Smart_Waste_Classification.ipynb
├── README.md
└── requirements.txt
```

## 🎯 Objective

The goal of this project is to demonstrate how Artificial Intelligence and Deep Learning can be used for automated waste classification and support smarter waste-management systems.

## 👨‍💻 Author

**Joydip Dey**

B.Tech Computer Science Engineering
Institute of Engineering & Management, Kolkata

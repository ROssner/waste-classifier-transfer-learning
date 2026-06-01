# ♻️ Waste Product Classifier — Transfer Learning & Fine-Tuning

Image classification model that automatically categorizes waste products using 
Transfer Learning and Fine-Tuning techniques.

## 🧠 About this project

Classifying waste correctly is a real-world problem with direct environmental impact.
This project uses a pre-trained CNN model and applies Transfer Learning and Fine-Tuning
to adapt it to waste product classification — achieving strong results without training
from scratch.

## 🛠️ Tech Stack

- Python
- PyTorch
- Transfer Learning (pre-trained CNN)
- Fine-Tuning
- Jupyter Notebook

## 📊 Approach

1. Loaded a pre-trained convolutional neural network
2. Froze base layers to preserve learned features
3. Replaced the classification head for the waste categories
4. Fine-tuned the model on the waste dataset
5. Evaluated accuracy on validation data

## 📁 Files

- `Final_Proj-Classify_Waste_Products_Using_TL-_FT-v1.ipynb` — Main notebook

## 🎓 Context

Developed as part of the **IBM AI Engineering Professional Certificate** program.

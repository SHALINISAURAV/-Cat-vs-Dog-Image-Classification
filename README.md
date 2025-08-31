# 🐱🐶 Cat vs Dog Image Classification

A deep learning project to classify images of **Cats** and **Dogs** using **Transfer Learning** with MobileNetV2.  
Achieved **98%+ validation accuracy** with a clean end-to-end pipeline.

---

## 📊 Dataset
- **Training set** → 20,000 images (Cats & Dogs, balanced).
- **Validation set** → 5,000 images.

---

## 🧠 Model
- Base Model: **MobileNetV2** (pretrained on ImageNet).
- Custom classification head for **binary classification (Cat/Dog)**.
- Optimizer: Adam
- Loss: Binary Crossentropy

---

## 📈 Training Results
- **Epochs**: 5  
- **Final Training Accuracy**: 98.49%  
- **Final Validation Accuracy**: 98.46%  
- **Observation**: Low loss, minimal overfitting.

---

## 🔍 Testing
- **Single image prediction** works with high confidence (Cat/Dog).  
- **Bulk evaluation** on validation set achieved >98% accuracy.  
- Model saved and reloaded successfully for inference.

---

## 🚀 Learnings
- Data preprocessing & augmentation  
- Transfer Learning with MobileNetV2  
- Model training, saving & reloading  
- Inference pipeline for single & multiple images  

---

## 👩‍💻 Author
**Shalini Saurav**  

---

## 📌 Future Work
- Deploy model via **Streamlit / Flask** for web app demo.  
- Try other pretrained models (ResNet, EfficientNet).  
- Hyperparameter tuning for further improvements.  

---

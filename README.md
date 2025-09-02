# 🩻 Pneumonia Detection from Chest X-Rays

## 📌 Overview
This project uses **Deep Learning (ResNet50 Transfer Learning)** to classify chest X-rays into:
- ✅ Normal
- 🫁 Pneumonia

Achieved **90%+ accuracy** using fine-tuned ResNet50 with data augmentation.

---

## ⚙️ Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Matplotlib
- Google Colab (for training)

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/pneumonia-detection.git
   cd pneumonia-detection
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Train the model:
   ```bash
   python X-Ray-Predictor.py
   ```

4. Test on new images:  
   Update the `img_path` in the script with your test X-ray.  
   The script will display the image and print:
   ```
   ✅ Normal   or   🫁 Pneumonia
   ```

---

## 📂 Dataset
Dataset: [Chest X-Ray Pneumonia (Kaggle)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

---

## 📊 Results
- Accuracy: **90–93%**
- Model: Fine-tuned ResNet50

---

## 📸 Sample Prediction
![Sample X-Ray](sample_images/example.png)

---

## 👨‍💻 Author
**Sachin Kumar**  
B.Tech Student | AI & Deep Learning Enthusiast

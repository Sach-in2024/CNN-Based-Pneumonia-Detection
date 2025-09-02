# 🩻 Pneumonia Detection from Chest X-Rays

## 📌 Overview
This project uses **Deep Learning (ResNet50 Transfer Learning)** to classify chest X-rays into:
- ✅ Normal
- 🫁 Pneumonia

Achieved **86% accuracy** using fine-tuned ResNet50 with data augmentation.

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
- Accuracy: **86-90%**
- Model: Fine-tuned ResNet50

---

## 📸 Sample Prediction
<img width="574" height="713" alt="Normal_Outcome" src="https://github.com/user-attachments/assets/b813dc6d-3a51-4fe8-9652-73a8e28ca1b2" />


---

## 👨‍💻 Author
**Sachin Kumar**  
B.Tech Student | AI & Deep Learning Enthusiast

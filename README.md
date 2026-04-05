# 🚀 AI-Based Image Classification using Intel oneAPI (oneDNN)

## 📌 Project Overview
This project implements an **image classification system** using a Convolutional Neural Network (CNN) with **TensorFlow**.  
It leverages **Intel oneAPI (oneDNN optimization)** to improve performance and reduce training time.

---

## 🎯 Objectives
- Build a deep learning model for image classification  
- Achieve high accuracy (~90%+)  
- Optimize performance using oneAPI (oneDNN)  
- Visualize training results  

---

## ⚙️ Technologies Used
- Python 🐍  
- TensorFlow / Keras  
- Intel oneAPI (oneDNN)  
- NumPy  
- Matplotlib  

---

## 📂 Dataset Structure
Student_Projects/
│
├── class1/
├── class2/


> Note: If train/test folders are not available, validation split is used.

---

## 🧠 Model Architecture
- MobileNetV2 (Pretrained)
- Global Average Pooling
- Dense Layer (ReLU)
- Dropout Layer
- Output Layer (Sigmoid)

---

## 🚀 Features
- High accuracy model  
- Faster training using oneDNN  
- Data augmentation  
- Automatic dataset handling  

---

## 📊 Results
- Accuracy: ~90%+  
- Reduced training time using oneAPI optimization  

---

## ▶️ How to Run

1. Clone the repository:
git clone https://github.com/Sprizenpro/Optimized-Deep-Learning-Model-for-Image-Classification-using-Intel-oneAPI.git


2. Install dependencies:
pip install -r requirements.txt


3. Run the notebook in Google Colab or Jupyter Notebook

4. Upload dataset and train model

---

## ⚡ oneAPI Optimization
This project uses:
os.environ["TF_ENABLE_ONEDNN_OPTS"] = "1"

to enable Intel oneDNN optimizations for faster computation.

---

## 📈 Output
- Training Accuracy Graph  
- Loss Graph  
- Final Accuracy Score  
- Saved Model (.h5 file)  

---

## 👨‍💻 Author
Selva Kumar  

---

## 📌 Conclusion
This project demonstrates how **Intel oneAPI optimization enhances deep learning performance**, achieving high accuracy and reduced training time.

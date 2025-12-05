# 🕵️‍♂️ Deepfake Detection System

## 📌 Overview
In an era of rising digital misinformation, distinguishing between authentic and manipulated media is critical. This project utilizes **Deep Learning** and **Computer Vision** techniques to detect Deepfake content with high accuracy.

We implemented a **Convolutional Neural Network (CNN)** architecture to analyze facial artifacts and inconsistencies in video frames/images to classify them as "Real" or "Fake."

## 🚀 Key Features
* **CNN Architecture:** Custom-built layers for feature extraction from image frames.
* **Data Preprocessing:** Automated resizing, normalization, and noise reduction techniques.
* **Binary Classification:** accurately distinguishes between legitimate and AI-generated media.
* **Visual Analysis:** Includes graphs for loss/accuracy curves and confusion matrices.

## 🛠️ Tech Stack

### 💻 Core Development
* **Language:** Python 🐍
* **Environment:** Jupyter Notebook / Google Colab 📓

### 🧠 Deep Learning & AI
* **Frameworks:** TensorFlow (Keras) / PyTorch
* **Architecture:** Custom CNN with Dropout and Batch Normalization layers.

### 👁️ Computer Vision & Processing
* **OpenCV (`cv2`):** Video frame extraction and artifact analysis.
* **Pillow (`PIL`):** Image preprocessing and resizing.

### 📊 Data & Visualization
* **Data Handling:** NumPy, Pandas
* **Visualization:** Matplotlib, Seaborn (Accuracy/Loss graphs).
* **Evaluation:** Scikit-learn (Confusion Matrix, Classification Reports).

### 🖥️ User Interface
* **Frontend:** Gradio / IPyWidgets (Integrated directly into `interface.ipynb`)

## 📂 Project Structure
```text
├── dd_enhanced.ipynb   # 🧠 Model Training & Evaluation Log
├── interface.ipynb     # 🖥️ User Interface for Testing
├── dataset/            # 📁 Dataset (Images/Videos)
└── README.md           # 📄 Project Documentation

# 🚀 Diabetic Retinopathy Classification – Hackathon Project  

## 📌 Team EHF  
**Members:**  
- Eraj Tanweer  
- Hunaiza Khan  
- Faisal Shahid  

## 📖 Overview  
This project implements a **deep learning model** using **TensorFlow and Keras** to classify **Diabetic Retinopathy** from retinal images. The goal is to build a robust **CNN-based model** that can effectively detect different stages of the disease, aiding in early diagnosis and treatment.  

## 📂 Project Pipeline  
### 1️⃣ Data Acquisition  
- Dataset: **Diabetic Retinopathy Balanced Dataset** from Kaggle  
- Downloaded using `kagglehub.dataset_download`  
- Verified dataset integrity  

### 2️⃣ Data Preprocessing  
- Split dataset into **training, validation, and test** sets  
- Implemented a function to count dataset size  

### 3️⃣ Data Augmentation  
Applied various transformations to improve generalization:  
- **Rescaling**: Normalize pixel values (0 to 1)  
- **Rotation, Shifting, Shearing, Zooming**: Enhance variability  
- **Horizontal Flip**: Increase diversity  
- **Flow from Directory**: Efficient data loading  

### 4️⃣ Model Architecture  
A **Convolutional Neural Network (CNN)** extracts spatial features from images with multiple layers.  

### 5️⃣ Model Compilation & Training  
- **Optimizer**: Adam for faster convergence  
- **Loss Function**: Categorical cross-entropy  
- **Evaluation Metric**: Accuracy  

### 6️⃣ Evaluation  
- Assessed **accuracy and loss** on the test set  
- Results indicate good generalization capability  

## 🎯 Challenges & Solutions  
✅ **Class Imbalance**: Used a balanced dataset to prevent bias  
✅ **Overfitting**: Implemented **dropout** and data augmentation  
✅ **Training Time**: Leveraged **GPU acceleration**  

## 🏆 Results  
The model achieved **high accuracy** in classifying diabetic retinopathy.  

## 🔥 Future Improvements  
- Fine-tune the model for better performance  
- Increase dataset diversity for improved generalization  

## 📜 Conclusion  
This hackathon project successfully implemented a **deep learning approach** for **Diabetic Retinopathy Classification**. The combination of **CNN architecture, balanced dataset, and augmentation techniques** resulted in an effective model.  

## 📌 Repository Contents  
- `notebooks/` – Jupyter notebooks for training & evaluation  
- `dataset/` – Processed dataset  
- `README.md` – Project documentation  

Our Model is uploaded to the google drive: https://drive.google.com/drive/folders/1O8FY2ZLvJTSVUQx261dyb-EZb-rJGJX4?usp=drive_link

# SkillCraft Internship - Task 03: Cats vs Dogs Classification using SVM 🐱🐶

## 🔍 Objective
Build a binary image classifier to distinguish between **cats** and **dogs** using a **Support Vector Machine (SVM)**.  
Since large image datasets are time-consuming to process, a **synthetic dataset** was created to simulate image classification.

---

## 🧠 Techniques Used
- Support Vector Machine (SVM)
- Synthetic data simulation (grayscale image-like data)
- Train/Test Split
- Model Evaluation (Confusion Matrix, Classification Report)

---

## 🛠️ Libraries Used
- `numpy`
- `scikit-learn`
- `matplotlib`

---

## 📊 Dataset Description
A synthetic dataset was generated to simulate a binary classification scenario:
- **1000 grayscale images** of size 32x32 pixels
  - 500 "cat" images: lower pixel intensities (mean ~0.3)
  - 500 "dog" images: higher pixel intensities (mean ~0.7)
- Images were flattened and normalized to create feature vectors.

---

## 🧪 Model Training and Evaluation
- **Model Used:** `SVC(kernel='linear')` from Scikit-learn
- **Train/Test Split:** 80% training, 20% testing
- **Evaluation Metrics:**
  - Accuracy
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-score)

---

## ✅ Results
The SVM classifier successfully learned to differentiate between cats and dogs based on synthetic image features with high accuracy.  
This task demonstrates the ability to apply machine learning to image classification even with simulated data.

---

## 📁 Project Files
```
├── SCT_ML_TASK03_CatsVsDogs_SVM.ipynb
├── README.md
```

---

## 👨‍💻 Author
**Shaik Rahamat Shareef**  
SkillCraft Machine Learning Internship  
GitHub: [https://github.com/Shareef-16](https://github.com/Shareef-16)

---

## 🔗 Task Output
- Notebook: [SCT_ML_TASK03_CatsVsDogs_SVM.ipynb](https://github.com/Shareef-16/SCT_ML_TASK03_CatsVsDogs_SVM/blob/main/SCT_ML_TASK03_CatsVsDogs_SVM.ipynb)
- Repo: [https://github.com/Shareef-16/SCT_ML_TASK03_CatsVsDogs_SVM](https://github.com/Shareef-16/SCT_ML_TASK03_CatsVsDogs_SVM)

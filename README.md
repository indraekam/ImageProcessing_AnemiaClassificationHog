# 🩺 Anemia Classification using Hemoglobin Image & HOG Features

This project is an end-to-end machine learning pipeline to classify anemia based on hemoglobin images taken from the **lower eyelid**.  
It leverages **Histogram of Oriented Gradients (HOG)** for feature extraction and a **Decision Tree Classifier** for prediction.

![Project Banner](https://img.shields.io/badge/ML-Powered-blueviolet?style=flat&logo=python)  
> Developed and evaluated entirely in **Google Colab** using Python.

---

## 🚀 Project Overview

- 📷 Input: RGB Image of hemoglobin from the eyelid (JPG)
- 🔍 Feature Extraction: HOG (Histogram of Oriented Gradients)
- 🧠 Model: Decision Tree Classifier
- 📊 Output: Anemia classification (`anemia` or `normal`)
- 📈 Evaluation: Accuracy, Precision, Recall, F1-score, Confusion Matrix

---

## 🧠 Workflow

```text
📁 Dataset Folder
   ├── Latih/
   │   ├── anemia/
   │   └── normal/
   └── Uji/
       ├── anemia/
       └── normal/

Step-by-step process:
1. Load and preprocess dataset
2. Resize and grayscale conversion
3. Extract HOG features
4. Train Decision Tree model
5. Evaluate model performance
6. Visualize confusion matrix
```

---

## 🛠️ Tech Stack & Tools

- Python 3.x (Google Colab)
- Scikit-learn
- Scikit-image
- Matplotlib
- mlxtend
- NumPy, tqdm, cv2
- [Google Drive Integration]

---

## 📊 Sample Results

| Metric         | Value     |
|----------------|-----------|
| Accuracy       | 92.5%     |
| Precision      | 93%       |
| Recall         | 91%       |
| F1-Score       | 92%       |

*(Replace with your actual results after final run)*

---

## 📁 How to Run

1. Upload the notebook to [Google Colab](https://colab.research.google.com)
2. Connect to your Google Drive and update the `BASE_PATH`
3. Run each cell sequentially
4. Model training and evaluation will be shown in notebook

---

## 📂 Repository Structure

```
📦 anemia-classification-hog
 ┣ 📄 TA_fix_PRO_final.ipynb
 ┣ 📄 README.md
 ┗ 📁 /dataset (optional)
```

---

## 👨‍💻 Author

**Indra Eka Mandriana S.Kom**  
_Machine Learning Engineer & Researcher_  
[LinkedIn](https://linkedin.com/in/your-link) | [GitHub](https://github.com/your-username) | [Email](mailto:your@email.com)

---

## ⭐ Star this repo if you like it!

> This project is part of my Machine Learning portfolio.  
Feel free to explore, fork, and collaborate!

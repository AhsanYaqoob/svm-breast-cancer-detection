# Breast Cancer Classification using Support Vector Machine (SVM)

This project applies Support Vector Machine models with different kernels (RBF and Linear) to classify breast cancer cell samples as benign or malignant. The dataset used is from the [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29).

## 📊 Dataset
- Features: Cell sample characteristics (e.g., Clump Thickness, Bare Nuclei)
- Target: Class (0 = Benign, 1 = Malignant)

## 🧠 Models Used
- SVM with RBF kernel
- SVM with Linear kernel

## ⚙️ Workflow
1. Load and clean data
2. Visualize basic stats
3. Preprocess and scale features
4. Train/test split
5. Train SVM models
6. Evaluate with:
   - Confusion Matrix
   - Precision, Recall, F1-score
   - Jaccard Score

## 📈 Results
RBF kernel performed slightly better on this dataset compared to the Linear kernel in terms of accuracy and F1-score.

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook svm_classification.ipynb

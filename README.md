# Task-6-KNN

# 🧠 Task 6: K-Nearest Neighbors (KNN) Classification

## 🎯 Objective
To understand the working of the **K-Nearest Neighbors (KNN)** algorithm and implement it for solving classification problems using standard machine learning tools.

---

## 🛠️ Tools & Libraries Used
- **Scikit-learn** – For model building and evaluation  
- **Pandas** – For data handling  
- **Matplotlib / Seaborn** – For visualization  

---

## 📋 Task Steps

1. **Choose a Classification Dataset**  
   Select a dataset suitable for classification (e.g., Iris Dataset).

2. **Normalize Features**  
   Normalize the input features to ensure fair distance calculations.

3. **Use `KNeighborsClassifier`**  
   Apply the KNN algorithm using Scikit-learn’s `KNeighborsClassifier`.

4. **Experiment with Different K Values**  
   Vary the number of neighbors (K) to observe changes in model performance.

5. **Evaluate the Model**  
   Use metrics like accuracy score and confusion matrix to assess performance.

6. **Visualize Decision Boundaries**  
   Create plots to show how KNN divides the feature space into class regions  
   *(works best with 2 features)*.

---

## 📊 Evaluation Metrics
- Accuracy Score  
- Confusion Matrix  
- Classification Report  
- Decision Boundary Plots *(for 2D visualizations)*  
 
---

## 📁 Dataset
You can use any classification dataset.  
**Example:** *Iris Dataset*  
🔗 [Click here to download dataset](https://www.kaggle.com/datasets/uciml/iris/data/Iris.cvs)
[Hand-Written Notes](file:///C:/Users/Dell/AppData/Local/Microsoft/Windows/INetCache/IE/1K86WGYW/New_Doc_06-03-2025_14.27[1].pdf)
---

## 📌 Notes
- KNN is a **lazy learner** that stores training data and delays computation until prediction.  
- Works best with **normalized, clean data**.  
- Suitable for **small to medium-sized datasets**.  

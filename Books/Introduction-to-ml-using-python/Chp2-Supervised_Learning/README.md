# Chapter 2: Supervised Learning

## 📌 What is Supervised Learning?
Supervised Learning is a type of machine learning where we train a model using **labeled data**.  
This means that for every input, we already know the correct output.

The goal is to learn a mapping from inputs to outputs so that the model can predict outcomes for new, unseen data.

---

## 🔍 Types of Supervised Learning

### 1. Classification
- The goal is to predict a **class label** from a predefined set of categories  
- Output is **discrete**

#### Types:
- **Binary Classification** → Two classes  
  - Example: Spam vs Not Spam  
- **Multi-class Classification** → More than two classes  
  - Example: Iris flower classification  

---

### 2. Regression
- The goal is to predict a **continuous numerical value**  
- Output is a **real number (float)**  

#### Example:
- Predicting house prices based on features like number of rooms, location, area, etc.

---

## 🧠 Important Concepts in Machine Learning

### Generalization
- The ability of a model to perform well on **unseen data**  
- A good model should generalize from training data to test data effectively  

---

### Overfitting
- Occurs when a model is **too complex** for the given data  
- The model learns the training data too well (including noise)  
- Results in **poor performance on new data**

---

### Underfitting
- Occurs when a model is **too simple**  
- The model fails to capture important patterns in the data  
- Performs poorly even on the training data  

---

## ⚖️ Model Complexity Trade-off
There is a **balance (sweet spot)** between underfitting and overfitting.

- Too simple → Underfitting  
- Too complex → Overfitting  
- Optimal complexity → Best generalization  

---

## 📊 Model Complexity vs Dataset Size
- Model complexity should match the amount and variety of data  
- Larger and more diverse datasets can support more complex models  
- Small datasets require simpler models to avoid overfitting  

💡 Note:  
Collecting more data often improves model performance and allows the use of more complex models.

---
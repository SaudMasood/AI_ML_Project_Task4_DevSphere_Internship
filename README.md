# 🤖 AI/ML Project Task 4 — DevSphere Internship

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&pause=1000&color=36BCF7&center=true&vCenter=true&width=850&lines=DevSphere+Internship;Artificial+Intelligence+%26+Machine+Learning;Week+4+Project;Neural+Networks+%7C+Classification+Models" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&height=3&section=header" />
</p>

<p align="center">

![DevSphere](https://img.shields.io/badge/DevSphere-Internship-2563EB?style=for-the-badge)

![Week](https://img.shields.io/badge/Week-04-FF8C00?style=for-the-badge)

![Domain](https://img.shields.io/badge/AI%20%26%20ML-Internship-8B5CF6?style=for-the-badge)

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge\&logo=python\&logoColor=white)

![Status](https://img.shields.io/badge/Status-Completed-22C55E?style=for-the-badge)

</p>

---

## 👨‍💻 Intern Information

| **Information** | **Details**                                |
| --------------- | ------------------------------------------ |
| 👤 **Intern**   | Saud Masood                                |
| 🏢 **Program**  | DevSphere Internship Program               |
| 🤖 **Domain**   | Artificial Intelligence & Machine Learning |
| 📅 **Week**     | Week 04                                    |
| 💻 **Language** | Python                                     |
| 🧠 **AI Task**  | Neural Networks                            |
| 📊 **ML Task**  | Classification                             |

---

# 🚀 Week 4 Overview

Week 4 focuses on two important Machine Learning concepts:

### 🤖 AI — Neural Networks Basics

Implement a basic neural network, train it on a dataset, and generate predictions.

### 📊 ML — Classification Models

Implement a classification model, train it on a classification dataset, make predictions, and calculate the accuracy score.

---

# 🤖 AI Task — Neural Networks Basics

## 📌 Topic

**Neural Networks Basics**

## 🎯 Objective

The objective is to implement a simple neural network that can:

* 🧠 Create a basic neural network model
* 📊 Train the model on a dataset
* 🔮 Generate predictions
* 📤 Show results
* 📝 Explain the workflow

## 🔄 Workflow

```text
📊 Dataset
     ↓
📂 Load Dataset
     ↓
⚙️ Data Preprocessing
     ↓
🧠 Neural Network
     ↓
🏋️ Model Training
     ↓
🔮 Predictions
     ↓
📤 Results
```

## 📊 Dataset

The neural network uses:

`student_scores_week4.csv`

| Feature      | Description             |
| ------------ | ----------------------- |
| `StudyHours` | Number of hours studied |
| `ExamScore`  | Student exam score      |

---

## 🧠 Neural Network Architecture

```text
Input Layer
     │
     │ StudyHours
     ↓
Hidden Layer
  10 Neurons
  ReLU
     │
     ↓
Output Layer
     │
     ↓
Exam Score
```

### Model Configuration

* Input: `1 feature`
* Hidden Layer: `10 neurons`
* Activation: `ReLU`
* Model: `MLPRegressor`
* Output: Predicted Exam Score

---

# 📊 ML Task — Classification Models

## 📌 Topic

**Classification Models**

## 🎯 Objective

The objective is to implement a classification model that can:

* 📂 Use a classification dataset
* 🧠 Train a classification model
* 🔮 Predict outputs
* 🎯 Calculate accuracy score

## 🔄 Workflow

```text
📊 Classification Dataset
          ↓
     📂 Load Data
          ↓
   🔍 Select Features
          ↓
    🧠 Train Model
          ↓
     🔮 Predictions
          ↓
    🎯 Accuracy Score
```

---

## 📊 Classification Dataset

File:

`student_classification.csv`

| StudyHours | Attendance | Passed |
| ---------: | ---------: | -----: |
|          1 |         50 |      0 |
|          2 |         55 |      0 |
|          2 |         60 |      0 |
|          3 |         65 |      0 |
|          4 |         70 |      1 |
|          5 |         72 |      1 |
|          5 |         75 |      1 |
|          6 |         78 |      1 |
|          7 |         80 |      1 |
|          8 |         85 |      1 |
|          9 |         90 |      1 |
|         10 |         95 |      1 |

### Target

```text
0 = Fail
1 = Pass
```

---

# 🧠 Classification Model

The project uses **Logistic Regression** for classification.

```text
Study Hours ───────┐
                   ├──► Logistic Regression ───► Pass / Fail
Attendance ────────┘
```

The model learns from the training data and predicts whether a student is likely to **Pass** or **Fail**.

---

# 🎯 Model Evaluation

The classification model is evaluated using:

```text
Accuracy Score
```

Accuracy measures the proportion of correctly predicted samples.

```text
Accuracy = Correct Predictions / Total Predictions
```

---

# 🛠️ Technologies Used

<p align="center">

<img src="https://skillicons.dev/icons?i=python" />

</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square\&logo=pandas\&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square\&logo=scikit-learn\&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat-square\&logo=googlecolab\&logoColor=white)

</p>

---

# 📁 Repository Structure

```text
AI_ML_Project_Task4_DevSphere_Internship/
│
├── 🤖 ai_week4_neural_network.py
├── 📊 ml_week4_classification.py
│
├── 📄 Week_4_AI_ML_Report.docx
│
├── 📊 student_scores_week4.csv
├── 📊 student_classification.csv
│
└── 📖 README.md
```

---

# 🔬 Project Workflow

### AI — Neural Network

```text
Dataset
  ↓
Preprocessing
  ↓
Neural Network
  ↓
Training
  ↓
Prediction
  ↓
Result
```

### ML — Classification

```text
Classification Dataset
  ↓
Train/Test Split
  ↓
Logistic Regression
  ↓
Prediction
  ↓
Accuracy Evaluation
```

---

# 📈 Learning Outcomes

Through Week 4, I practiced:

* 🧠 Understanding basic neural networks
* ⚙️ Creating a neural network model
* 📊 Preparing datasets
* 🏋️ Training Machine Learning models
* 🔮 Generating predictions
* 📚 Understanding classification
* 📈 Implementing Logistic Regression
* 🎯 Evaluating model accuracy
* 🔄 Understanding the ML workflow

---

# ✅ Completion Status

| Task                             | Status      |
| -------------------------------- | ----------- |
| 🤖 Neural Network Implementation | ✅ Completed |
| 🧠 Neural Network Training       | ✅ Completed |
| 🔮 Neural Network Predictions    | ✅ Completed |
| 📊 Classification Dataset        | ✅ Completed |
| 🧠 Classification Model          | ✅ Completed |
| 🔮 Classification Predictions    | ✅ Completed |
| 🎯 Accuracy Score                | ✅ Completed |

---

# 📚 Week 4 Summary

> **Build → Train → Predict → Evaluate**

Week 4 provided practical experience with **Neural Networks** and **Classification Models**, including model training, prediction, and evaluation.

---

## 👨‍💻 Author

### **Saud Masood**

🤖 AI/ML Intern
🏢 DevSphere Internship Program
💻 Artificial Intelligence & Machine Learning

---

<p align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer&text=Week%204%20Completed!&fontSize=28&fontColor=ffffff&animation=twinkling" />

</p>

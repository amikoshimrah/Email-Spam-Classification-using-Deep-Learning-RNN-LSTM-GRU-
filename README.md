# 📧 Email Spam Classification using RNN, LSTM & GRU

## 🧠 Project Overview
This project demonstrates an end-to-end **Email Spam Classification** system using **Deep Learning**.  
By leveraging **Recurrent Neural Networks (RNN)**, **Long Short-Term Memory (LSTM)**, and **Gated Recurrent Unit (GRU)** models, the system intelligently classifies emails as *spam* or *non-spam* based on their content.

---

## 🚀 Objectives
- Build deep learning models capable of identifying spam messages.
- Compare RNN, LSTM, and GRU architectures for accuracy and efficiency.
- Perform data preprocessing, text cleaning, and tokenization.
- Visualize model performance metrics (accuracy, loss).

---

## 🧩 Workflow Summary

### 1. **Data Acquisition**
- Dataset: [Spam Mails Dataset (Kaggle)](https://www.kaggle.com/datasets/venky73/spam-mails-dataset)
- Downloaded using `kagglehub` and loaded into pandas for preprocessing.

### 2. **Data Preprocessing**
- Text cleaning: punctuation, numbers, and stopword removal.
- Tokenization and padding using TensorFlow’s `Tokenizer` and `pad_sequences`.
- Label encoding for spam (1) and ham (0).

### 3. **Model Building**
Developed three separate models for performance comparison:
- **Simple RNN Model**
- **LSTM Model**
- **GRU Model**

Each model includes:
- Embedding layer  
- Recurrent layers (RNN/LSTM/GRU)  
- Dense + Dropout layers for optimization  

### 4. **Training & Evaluation**
- Split dataset into train/test sets (80/20 ratio)
- Implemented **EarlyStopping** to prevent overfitting
- Compared metrics:
  - Accuracy
  - Validation Loss
  - Training Curves

### 5. **Results**
- All models successfully classified spam vs ham emails with high accuracy.
- **LSTM** and **GRU** models showed superior generalization compared to Simple RNN.
- Visualizations of accuracy/loss trends were plotted using Matplotlib and Seaborn.

---

## 🧮 Technologies Used
- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **KaggleHub**

---

## 📊 Key Takeaways
- Learned comparative performance of RNN-based architectures.
- Enhanced understanding of text preprocessing and sequence modeling.
- Demonstrated how recurrent networks handle sequential dependencies in text data.

---

## 🙌 Mentors
- **Chirag Jhumkhawala**  
- **KARKAVELRAJA J**  
- **Pranav**

---

## 🔗 Resources
- 📂 Dataset: [Spam Mails Dataset – Kaggle](https://www.kaggle.com/datasets/venky73/spam-mails-dataset)  
  

---

## 🏷️ Tags
`Deep Learning` `NLP` `TensorFlow` `Machine Learning` `Email Spam Detection` `RNN` `LSTM` `GRU`


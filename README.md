# 🏭 Industrial Safety NLP Chatbot

🚀 **AI-Powered Chatbot for Predicting and Highlighting Safety Risks in Industrial Environments**

---

## 📌 Problem Statement
Industrial environments continue to face safety challenges where employees and third-party workers experience accidents, sometimes leading to severe injuries or fatalities.  

This project leverages **Natural Language Processing (NLP)** and **Machine Learning/Deep Learning** to build a chatbot that analyzes incident descriptions and predicts **risk severity**, helping organizations take proactive safety measures.

---

## 🎯 Objective
Design and develop an **ML/DL-based chatbot** that:
- Understands accident descriptions  
- Predicts **Accident Level** and **Potential Risk Level**  
- Highlights **critical safety risks**  
- Assists safety professionals in decision-making  

---

## 📂 Dataset Overview
📊 Source: Industrial Safety and Health Analytics Database (Kaggle)

The dataset contains accident records from:
- 🌍 12 plants  
- 🌎 3 countries  

### 🧾 Features
- **Date**: Timestamp of the accident  
- **Country**: Location (anonymized)  
- **Local**: City (anonymized)  
- **Industry Sector**: Type of industry  
- **Accident Level**: Severity (I to VI)  
- **Potential Accident Level**: Possible severity  
- **Gender**: Male/Female  
- **Employee Type**: Employee or Third Party  
- **Critical Risk**: Type of risk involved  
- **Description**: Detailed accident narrative  

---

## 🧠 Solution Approach

### 🔹 Data Preprocessing
- Text cleaning (stopwords, punctuation removal)
- Tokenization & Lemmatization
- Handling class imbalance

### 🔹 NLP Techniques
- TF-IDF / Word Embeddings  
- Feature extraction from incident descriptions  

### 🔹 Models Used
- Machine Learning:
  - Logistic Regression  
  - Random Forest  
  - XGBoost  

- Deep Learning:
  - LSTM  
  - Transformer-based models (optional)

### 🔹 Chatbot Development
- Input: User enters incident description  
- Output:
  - Predicted Accident Level  
  - Potential Risk Level  
  - Safety insights  

---

## 🛠️ Tech Stack

- **Languages**: Python  
- **Libraries**:  
  - Pandas, NumPy  
  - Scikit-learn  
  - TensorFlow / Keras  
  - NLTK / SpaCy  
- **Visualization**: Matplotlib, Seaborn  
- **Deployment (Optional)**: Streamlit / Flask  

---

## 🔄 Workflow

1. Data Collection & Understanding  
2. Exploratory Data Analysis (EDA)  
3. Text Preprocessing  
4. Feature Engineering  
5. Model Training & Evaluation  
6. Chatbot Integration  
7. Deployment  

---

## 📊 Expected Outcomes
- Accurate classification of accident severity  
- Early identification of high-risk scenarios  
- Improved workplace safety awareness  
- Decision support for safety professionals  

---

## 🚀 Future Enhancements
- Real-time chatbot deployment  
- Integration with IoT safety systems  
- Multilingual support  
- Advanced transformer models (BERT, GPT)  

---

## 📫 Contact
👤 Amrutha  
💼 Data Scientist | AI Enthusiast  

---

✨ *Using AI to build safer industrial environments.*

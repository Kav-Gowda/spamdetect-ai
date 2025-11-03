# SpamDetect AI

An intelligent SMS spam classification project built using Machine Learning and Deep Learning techniques.  
The model combines traditional NLP-based classifiers and a BiLSTM neural network for accurate spam detection.

---

## 🚀 Overview
SpamDetect AI identifies and filters spam messages using text preprocessing, tokenization, and word embeddings.  
It evaluates multiple ML models (Naive Bayes, Logistic Regression, SVM, etc.) before training a deep BiLSTM for final predictions.

---

## 🧠 Tech Stack
- Python  
- TensorFlow / Keras  
- Scikit-learn  
- NLTK  
- WordCloud  
- Matplotlib, Seaborn  

---

## 📊 Key Features
- Text cleaning and lemmatization pipeline  
- Word frequency analysis and visualizations  
- Evaluation of multiple ML classifiers  
- Bidirectional LSTM model for superior accuracy  
- Visualization of loss, accuracy, and confusion matrices  

---

## 🧾 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-username>/spamdetect-ai.git
   cd spamdetect-ai
   ```
2. Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```

3. Run the script:
  ```bash
  python SpamDetect_AI.py
  ```

📈 Results

Achieved >95% accuracy on the SMS Spam dataset using a BiLSTM model.

📄 License

Licensed under the MIT License — see the LICENSE file for details.

# 📩 Spam Detection using Naive Bayes & NLP

A machine learning project that detects whether a text message is **Spam** or **Ham (Not Spam)** using **Natural Language Processing (NLP)** and the **Multinomial Naive Bayes** algorithm.

---

## 📌 Project Overview

This project uses text preprocessing techniques and a Naive Bayes classifier to classify SMS messages as spam or ham. The model is trained on a labeled SMS dataset and allows users to test their own messages through user input.

---

## ✨ Features

- Text preprocessing using NLP
- Stopword removal and punctuation cleaning
- Text vectorization using CountVectorizer
- Spam classification using Multinomial Naive Bayes
- Model evaluation with:
  - Accuracy Score
  - Classification Report
  - Confusion Matrix
- User input for real-time message prediction

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- NLTK
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

The project uses the **SMS Spam Collection Dataset**, containing labeled SMS messages categorized as:

- **Ham** (Not Spam)
- **Spam**

---

## ⚙️ Workflow

1. Load the dataset
2. Clean and preprocess text
3. Convert text into numerical features using CountVectorizer
4. Split data into training and testing sets
5. Train the Multinomial Naive Bayes model
6. Evaluate model performance
7. Predict custom user messages

---

## 📊 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## 🚀 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Install the required libraries

   ```bash
   pip install pandas numpy matplotlib nltk scikit-learn
   ```

3. Open the Jupyter Notebook.

4. Run all cells.

5. Enter a custom message when prompted to check whether it is **Spam** or **Ham**.

---

## 📁 Project Structure

```
Spam Detection/
│── SpamDetect.ipynb
│── spam.csv
│── README.md
```

---

## 🎯 Future Improvements

- Improve text preprocessing
- Use TF-IDF Vectorizer
- Compare multiple machine learning algorithms
- Build a Streamlit web application
- Deploy the model online

---

## 👨‍💻 Author

**Navdeep**

If you found this project useful, consider giving it a ⭐ on GitHub.
